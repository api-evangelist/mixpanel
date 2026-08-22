# Mixpanel (mixpanel)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
