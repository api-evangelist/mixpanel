# Mixpanel GraphQL Schema

Conceptual GraphQL schema for the [Mixpanel](https://mixpanel.com) product analytics platform. Mixpanel provides a suite of REST APIs — Ingestion, Query, Engage, Export, Identity, Lexicon/Schemas, Service Accounts, Annotations, GDPR/CCPA, and Warehouse Connectors — that this schema maps into a unified GraphQL surface.

- **Developer docs**: https://developer.mixpanel.com/reference/
- **GitHub organization**: https://github.com/mixpanel
- **Schema file**: [mixpanel-schema.graphql](mixpanel-schema.graphql)

## Type Summary

| Domain | Types |
|---|---|
| Events | `Event`, `EventProperties`, `EventInput` |
| Users | `UserProfile`, `UserProperties`, `UserProfileInput`, `UserDistinct` |
| Groups | `GroupProfile`, `GroupProperties`, `GroupProfileInput` |
| Lookup Tables | `LookupTable`, `LookupTableRow` |
| Funnels | `Funnel`, `FunnelStep`, `FunnelResults`, `FunnelStepResult`, `FunnelBreakdown` |
| Retention | `Retention`, `RetentionInterval` |
| Segmentation | `Segmentation`, `SegmentResult`, `PropertyValues` |
| Cohorts | `Cohort`, `CohortFilter`, `CohortDefinition` |
| Dashboards | `Dashboard`, `DashboardReport`, `BoardReport` |
| Insights | `Insight`, `InsightFilter`, `InsightQuery` |
| Flows | `Flow`, `FlowPath`, `FlowStep` |
| Experiments | `Experiment`, `ExperimentVariant`, `ExperimentResult`, `VariantMetric` |
| Annotations | `Annotation`, `AnnotationInput` |
| Identity | `Identity`, `Alias` |
| Data Export | `DataExport`, `ExportJob` |
| Lexicon | `Lexicon`, `LexiconEntry` |
| Schema / Governance | `Schema`, `SchemaProperty` |
| Transforms | `Transform`, `TransformFilter` |
| Lookup (join) | `Lookup` |
| Service Accounts | `ServiceAccount`, `ProjectMembership` |
| Organization / Project | `APIProject`, `Organization`, `User`, `Role`, `Permission` |
| Compliance | `ComplianceRequest` |
| Pipelines | `DataPipeline` |
| Utility | `DateRange`, `DateRangeInput` |
| Enums | `DataType`, `RetentionType`, `FunnelOrderType`, `ExportJobStatus`, `PipelineStatus`, `ComplianceRequestType`, `ComplianceRequestStatus`, `RoleLevel`, `PropertyType` |

## Domain Coverage

### Event Ingestion

The `trackEvent` and `importEvents` mutations map to the Mixpanel Ingestion API (`/track` and `/import`). `Event` and `EventProperties` represent the canonical shape of a tracked event including standard Mixpanel super-properties (browser, OS, city, referrer) plus an open `extra: JSON` field for arbitrary properties.

### Query and Segmentation

`segmentation` and `funnelResults` queries correspond to the Query API (`/api/2.0/segmentation`, `/api/2.0/funnels`). `Segmentation` and `SegmentResult` capture time-series event breakdowns; `FunnelResults` wraps step-by-step conversion data with optional `FunnelBreakdown` by property.

### Retention

`Retention` and `RetentionInterval` model the `/api/2.0/retention` endpoint. The `RetentionType` enum covers `BIRTH` (first-time) and `COMPOUNDED` (recurring) retention modes.

### People / Engage

`UserProfile` and `UserProperties` represent a Mixpanel People profile. `userProfiles` maps to the Engage API (`/api/2.0/engage`) with JQL-style `where` filtering and cursor-based pagination via `sessionId`.

### Group Analytics

`GroupProfile` and `GroupProperties` support B2B account-level analytics, matching the Group Profiles ingestion endpoints.

### Cohorts

`Cohort`, `CohortDefinition`, and `CohortFilter` reflect the cohort objects returned by `/api/2.0/cohorts/list`. The definition captures the behavioral filter logic used to qualify users.

### Lexicon and Schema Governance

`Lexicon`, `LexiconEntry`, `Schema`, and `SchemaProperty` map to the Lexicon Schemas API (`/api/app/projects/{id}/schemas`). Schemas can govern both event definitions and user/group properties.

### Identity Management

`Identity`, `Alias`, and `UserDistinct` cover ID Merge operations: linking anonymous IDs to known user IDs, creating aliases, and merging distinct IDs via the Identity API.

### Annotations

`Annotation` maps to the Annotations API. Annotations mark points in time (releases, campaigns, data anomalies) visible on Mixpanel charts.

### Data Export

`ExportJob` models batch raw-event export jobs. `DataExport` captures the query parameters (date range, event filter, JQL `where` clause) sent to the Export API (`/api/2.0/export`).

### Compliance (GDPR / CCPA)

`ComplianceRequest` covers both data-retrieval and data-deletion tasks submitted via the GDPR/CCPA API. The `ComplianceRequestStatus` enum tracks the task lifecycle from `PENDING` through `COMPLETE` or `FAILED`.

### Data Pipelines / Warehouse Connectors

`DataPipeline` represents a configured warehouse connector (BigQuery, Snowflake, Redshift, etc.). Mutations cover create, pause, resume, delete, and trigger-run operations matching the Warehouse Connectors API.

### Transforms

`Transform` and `TransformFilter` represent ingestion-time transformation rules that rewrite or enrich events before they are stored.

### Service Accounts and Access Control

`ServiceAccount`, `Organization`, `APIProject`, `User`, `Role`, and `Permission` form the organizational management layer. Service accounts can be scoped to specific projects with specific roles (`VIEWER`, `ANALYST`, `ADMIN`, `OWNER`).

### Web Experimentation

`Experiment`, `ExperimentVariant`, `ExperimentResult`, and `VariantMetric` model Mixpanel's A/B testing surface, capturing variant configuration and statistical outcome data.

## Scalars

| Scalar | Description |
|---|---|
| `JSON` | Arbitrary JSON value for open-ended property bags |
| `DateTime` | ISO 8601 timestamp with timezone |
| `Date` | Calendar date (YYYY-MM-DD) |

## Authentication

Mixpanel uses two authentication schemes:

- **Project token** — passed in event ingestion payloads; identifies the destination project.
- **Service Account credentials** (HTTP Basic Auth) — used for all Query, Export, Lexicon, and management API calls. Username and secret are issued per service account.

OAuth 2.0 is supported for user-delegated access in certain contexts.

## Rate Limits

- Ingestion API: ~2,000 events/second per IP recommended
- Query API: 60 queries/hour, 5 concurrent
- Batch import: 2,000 events per request

See https://developer.mixpanel.com/reference/rate-limits for current limits.
