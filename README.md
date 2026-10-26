# Power BI (power-bi)

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

Microsoft Power BI is a business analytics service that delivers insights to enable fast, informed decisions. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards.

**APIs.json:** [https://powerbi.microsoft.com](https://powerbi.microsoft.com)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Business Intelligence
- Dashboards
- Data Analysis
- Reporting
- Visualization

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Power BI REST API

The Power BI REST API provides service endpoints for embedding, administration, governance, and user resources.

- **Human URL:** [https://docs.microsoft.com/en-us/rest/api/power-bi/](https://docs.microsoft.com/en-us/rest/api/power-bi/)
- **Base URL:** `https://api.powerbi.com`

#### Tags

- Dashboards
- Datasets
- Embeddings
- Reports
- REST

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/rest/api/power-bi/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/powerbi/data-plane/Microsoft.PowerBI/stable/v1.0/powerbi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/power-bi-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/power-bi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/power-bi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/power-bi-rest-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://docs.microsoft.com/en-us/power-bi/developer/embedded/get-azuread-access-token)
- [Getting Started](https://docs.microsoft.com/en-us/power-bi/developer/embedded/embedding-content)
- [Rate Limits](https://docs.microsoft.com/en-us/power-bi/developer/automation/api-rest-api-limitations)
- [SDK](https://docs.microsoft.com/en-us/javascript/api/overview/powerbi/)
- [Changelog](https://docs.microsoft.com/en-us/power-bi/developer/embedded/embedded-analytics-power-bi-changelog)
- [Troubleshooting](https://learn.microsoft.com/en-us/power-bi/developer/embedded/troubleshoot-rest-api)

### Power BI Embedded

Azure service that enables ISVs and developers to embed Power BI visuals, reports, and dashboards into their applications.

- **Human URL:** [https://azure.microsoft.com/en-us/services/power-bi-embedded/](https://azure.microsoft.com/en-us/services/power-bi-embedded/)
- **Base URL:** `https://api.powerbi.com`

#### Tags

- Azure
- Embedded
- Integration

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/power-bi/developer/embedded/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/power-bi-embedded/)
- [Sandbox](https://playground.powerbi.com/)
- [Code Examples](https://github.com/Microsoft/PowerBI-Developer-Samples)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/power-bi-embedded/)
- [Getting Started](https://learn.microsoft.com/en-us/power-bi/developer/embedded/embed-organization-app)
- [Authentication](https://learn.microsoft.com/en-us/power-bi/developer/embedded/embed-tokens)
- [SDK](https://learn.microsoft.com/en-us/javascript/api/overview/powerbi/embedded-analytics-client-api)
- [SDK](https://github.com/microsoft/PowerBI-CSharp)
- [Postman Collection](collections/power-bi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/power-bi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power BI Management API

API for managing Power BI capacity, workspaces, and tenant settings.

- **Human URL:** [https://docs.microsoft.com/en-us/rest/api/power-bi/admin](https://docs.microsoft.com/en-us/rest/api/power-bi/admin)
- **Base URL:** `https://api.powerbi.com/v1.0/myorg/admin`

#### Tags

- Administration
- Governance
- Management

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/rest/api/power-bi/admin)
- [Authentication](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-reference)
- [Getting Started](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-health)
- [Postman Collection](collections/power-bi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/power-bi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power BI Push Datasets API

The Push Datasets API enables real-time data streaming by allowing applications to create push datasets and post rows of data directly into Power BI datasets.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/power-bi/push-datasets](https://learn.microsoft.com/en-us/rest/api/power-bi/push-datasets)
- **Base URL:** `https://api.powerbi.com`

#### Tags

- Datasets
- Push
- Real-Time
- Streaming

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-bi/push-datasets)
- [Rate Limits](https://learn.microsoft.com/en-us/power-bi/developer/embedded/push-datasets-limitations)
- [Authentication](https://learn.microsoft.com/en-us/power-bi/developer/embedded/get-azuread-access-token)
- [Postman Collection](collections/power-bi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/power-bi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power BI Report Server REST API

The Power BI Report Server REST API provides programmatic access to report server catalog objects such as folders, reports, KPIs, data sources, datasets, refresh plans, and subscriptions.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/power-bi-report/](https://learn.microsoft.com/en-us/rest/api/power-bi-report/)
- **Base URL:** `https://api.powerbi.com`

#### Tags

- On-Premises
- Report Server
- Reports
- SSRS

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/power-bi-report/)
- [Getting Started](https://learn.microsoft.com/en-us/power-bi/report-server/rest-api)
- [Changelog](https://learn.microsoft.com/en-us/power-bi/report-server/changelog)
- [Release Notes](https://learn.microsoft.com/en-us/power-bi/report-server/whats-new)
- [Postman Collection](collections/power-bi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/power-bi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power BI Visuals API

The Power BI Visuals API enables developers to create custom visuals that can be used in Power BI reports and dashboards, extending the built-in visualization capabilities.

- **Human URL:** [https://learn.microsoft.com/en-us/power-bi/developer/visuals/](https://learn.microsoft.com/en-us/power-bi/developer/visuals/)
- **Base URL:** `https://api.powerbi.com`

#### Tags

- Charts
- Custom Visuals
- Visualization
- Visuals

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-bi/developer/visuals/)
- [API Reference](https://learn.microsoft.com/en-us/power-bi/developer/visuals/visual-api)
- [Getting Started](https://learn.microsoft.com/en-us/power-bi/developer/visuals/develop-power-bi-visuals)
- [Changelog](https://learn.microsoft.com/en-us/power-bi/developer/visuals/changelog)
- [Authentication](https://learn.microsoft.com/en-us/power-bi/developer/visuals/authentication-api)
- [Postman Collection](collections/power-bi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/power-bi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://app.powerbi.com)
- [Developer Portal](https://powerbi.microsoft.com/en-us/developers/)
- [Blog](https://powerbi.microsoft.com/en-us/blog/)
- [Support](https://powerbi.microsoft.com/en-us/support/)
- [Status Page](https://powerbi.microsoft.com/en-us/status/)
- [Terms of Service](https://powerbi.microsoft.com/en-us/terms-of-service/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Repository](https://github.com/Microsoft/PowerBI-JavaScript)
- [GitHub Repository](https://github.com/microsoft/PowerBI-Developer-Samples)
- [LinkedIn](https://www.linkedin.com/showcase/microsoft-power-bi/)
- [X (Twitter)](https://twitter.com/MSPowerBI)
- [YouTube](https://www.youtube.com/user/mspowerbi)
- [Documentation](https://learn.microsoft.com/en-us/power-bi/)
- [Pricing](https://www.microsoft.com/en-us/power-platform/products/power-bi/pricing)
- [Sign Up](https://app.powerbi.com/signupredirect?pbi_source=web)
- [Login](https://app.powerbi.com/signin)
- [Release Notes](https://learn.microsoft.com/en-us/power-bi/fundamentals/whats-new)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/powerbi)
- [JSON-LD](json-ld/power-bi-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/power-bi-dataset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/power-bi-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [SDK](https://github.com/microsoft/PowerBI-CSharp)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
