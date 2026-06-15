# Mixpanel (mixpanel)

Mixpanel is a business analytics service company that tracks user interactions with web and mobile applications and provides tools for targeted communication with them.

**APIs.json:** [https://mixpanel.com](https://mixpanel.com)

## Scope

- **Type:** Index

## Tags

- Analytics
- Data Analysis
- Event Tracking
- Product Analytics
- User Behavior

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-30

## APIs

### Mixpanel Ingestion API

API for sending event data to Mixpanel for tracking and analysis, including importing events, tracking events, managing user profiles, group profiles, and lookup tables.

- **Human URL:** [https://developer.mixpanel.com/reference/ingestion-api](https://developer.mixpanel.com/reference/ingestion-api)
- **Base URL:** `https://api.mixpanel.com`

#### Tags

- Analytics
- Events
- Group Profiles
- Ingestion
- Tracking
- User Profiles

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/ingestion-api)
- [OpenAPI](https://developer.mixpanel.com/reference/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/mixpanel-ingestion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Query API

API for querying and retrieving analytics data from Mixpanel, including cohorts, funnels, insights, retention, segmentation, activity feeds, and event breakdowns.

- **Human URL:** [https://developer.mixpanel.com/reference/query-api](https://developer.mixpanel.com/reference/query-api)
- **Base URL:** `https://mixpanel.com/api`

#### Tags

- Analytics
- Cohorts
- Data Export
- Funnels
- Query
- Retention
- Segmentation

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/query-api)
- [OpenAPI](https://developer.mixpanel.com/reference/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/mixpanel-query-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Data Pipelines API

API for creating, managing, and monitoring data export pipelines in Mixpanel, including creating, editing, pausing, resuming, and deleting pipelines.

- **Human URL:** [https://developer.mixpanel.com/reference/overview-2](https://developer.mixpanel.com/reference/overview-2)
- **Base URL:** `https://data.mixpanel.com`

#### Tags

- Data Pipeline
- Export
- Import

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/raw-data-export-api)
- [OpenAPI](https://developer.mixpanel.com/reference/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/mixpanel-data-pipelines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-data-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-data-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Identity API

API for managing user identity in Mixpanel, including creating identities, creating aliases, and merging identities to accurately resolve users across multiple devices.

- **Human URL:** [https://developer.mixpanel.com/reference/create-identity](https://developer.mixpanel.com/reference/create-identity)
- **Base URL:** `https://api.mixpanel.com`

#### Tags

- ID Merge
- Identity
- User Management

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/create-identity)
- [OpenAPI](openapi/mixpanel-identity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Event Export API

API for downloading raw event data as it is received and stored within Mixpanel, complete with all event properties including distinct_id and exact timestamps.

- **Human URL:** [https://developer.mixpanel.com/reference/raw-event-export](https://developer.mixpanel.com/reference/raw-event-export)
- **Base URL:** `https://data.mixpanel.com/api/2.0`

#### Tags

- Data Export
- Events
- Raw Data

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/raw-event-export)
- [OpenAPI](openapi/mixpanel-event-export-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-event-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-event-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Lexicon Schemas API

API for syncing your internal data dictionary or tracking plan with Mixpanel using schemas, allowing you to create, replace, retrieve, and delete schema definitions that describe the data you send to Mixpanel.

- **Human URL:** [https://developer.mixpanel.com/reference/lexicon-schemas-api](https://developer.mixpanel.com/reference/lexicon-schemas-api)
- **Base URL:** `https://mixpanel.com/api/app`

#### Tags

- Data Dictionary
- Data Governance
- Lexicon
- Schemas

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/lexicon-schemas-api)
- [OpenAPI](openapi/mixpanel-lexicon-schemas-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-lexicon-schemas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-lexicon-schemas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Service Accounts API

API for programmatically managing service accounts within your organization, including creating, deleting, listing service accounts, and managing their project memberships.

- **Human URL:** [https://developer.mixpanel.com/reference/service-accounts-api](https://developer.mixpanel.com/reference/service-accounts-api)
- **Base URL:** `https://mixpanel.com/api/app`

#### Tags

- Administration
- Authentication
- Service Accounts

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/service-accounts-api)
- [OpenAPI](openapi/mixpanel-service-accounts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-service-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-service-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Annotations API

API for creating, retrieving, updating, and deleting annotations that label specific points in time on Mixpanel charts with descriptions, useful for marking product launches, campaigns, or data anomalies.

- **Human URL:** [https://developer.mixpanel.com/reference/create-annotation](https://developer.mixpanel.com/reference/create-annotation)
- **Base URL:** `https://mixpanel.com/api/app`

#### Tags

- Annotations
- Charts
- Reports

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/create-annotation)
- [OpenAPI](openapi/mixpanel-annotations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-annotations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-annotations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel GDPR and CCPA API

API for submitting data retrieval and deletion requests to help meet GDPR and CCPA compliance requirements, including creating and checking the status of retrieval and deletion tasks.

- **Human URL:** [https://developer.mixpanel.com/reference/gdpr-api](https://developer.mixpanel.com/reference/gdpr-api)
- **Base URL:** `https://mixpanel.com/api/app`

#### Tags

- CCPA
- Compliance
- Data Deletion
- Data Retrieval
- GDPR
- Privacy

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/gdpr-api)
- [OpenAPI](openapi/mixpanel-gdpr-ccpa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-gdpr-ccpa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-gdpr-ccpa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Warehouse Connectors API

API for connecting a data warehouse to import events, users, groups, and lookup tables into Mixpanel, and for manually triggering specific warehouse import runs.

- **Human URL:** [https://developer.mixpanel.com/reference/warehouse-connectors-api](https://developer.mixpanel.com/reference/warehouse-connectors-api)
- **Base URL:** `https://mixpanel.com/api/app`

#### Tags

- Connectors
- Data Import
- Integrations
- Warehouse

#### Properties

- [Documentation](https://developer.mixpanel.com/reference/warehouse-connectors-api)
- [OpenAPI](openapi/mixpanel-warehouse-connectors-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mixpanel-warehouse-connectors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-warehouse-connectors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mixpanel Webhooks

Outbound webhook surfaces delivered by Mixpanel to customer-hosted HTTPS endpoints, covering Custom Alert notifications (fired from reports configured in Project Settings) and Cohort Sync Custom Webhooks (full and incremental cohort membership change deliveries).

- **Human URL:** [https://docs.mixpanel.com/docs/features/alerts](https://docs.mixpanel.com/docs/features/alerts)
- **Base URL:** `https://example.com/mixpanel/webhook`

#### Tags

- Alerts
- Cohort Sync
- Notifications
- Webhooks

#### Properties

- [Documentation](https://docs.mixpanel.com/docs/features/alerts)
- [Documentation](https://docs.mixpanel.com/docs/cohort-sync/overview)
- [Documentation](https://docs.mixpanel.com/docs/cohort-sync/webhooks)
- [AsyncAPI](asyncapi/mixpanel-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/mixpanel-annotations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-annotations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-data-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-data-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-event-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-event-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-gdpr-ccpa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-gdpr-ccpa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-ingestion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-ingestion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-lexicon-schemas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-lexicon-schemas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-service-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-service-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mixpanel-warehouse-connectors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mixpanel-warehouse-connectors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/mixpanel-inc-)
- [Portal](https://developer.mixpanel.com/)
- [Getting Started](https://developer.mixpanel.com/docs/getting-started)
- [Authentication](https://developer.mixpanel.com/reference/authentication)
- [S D Ks](https://developer.mixpanel.com/docs/sdks)
- [Rate Limits](https://developer.mixpanel.com/reference/rate-limits)
- [A P I  Status](https://www.mixpanelstatus.com/)
- [Changelog](https://docs.mixpanel.com/changelogs)
- [GitHub Organization](https://github.com/mixpanel)
- [Integrations](https://mixpanel.com/partners/integrations)
- [Security](https://mixpanel.com/legal/security-overview/)
- [Login](https://mixpanel.com/login/)
- [Sign Up](https://mixpanel.com/register/)
- [Terms of Service](https://mixpanel.com/legal/terms-of-use)
- [Privacy Policy](https://mixpanel.com/legal/privacy-policy)
- [Pricing](https://mixpanel.com/pricing)
- [Blog](https://mixpanel.com/blog)
- [Support](https://mixpanel.com/get-support)
- [JSON-LD](json-ld/mixpanel-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/mixpanel-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mixpanel-user-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mixpanel-funnel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [M C P Server](https://github.com/mixpanel/mcp-go)
- [Agent Skill](https://github.com/mixpanel/ai-plugins)
- [L L Ms Txt](https://developer.mixpanel.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
