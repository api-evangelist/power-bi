# Power BI (power-bi)

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
