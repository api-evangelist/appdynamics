# AppDynamics (appdynamics)

AppDynamics, now part of Cisco, is an application performance monitoring (APM) and observability platform that provides full-stack visibility into application, business, and infrastructure performance. The platform offers REST APIs for controller management, metrics, alerts, analytics events, database monitoring, and the next-generation Cisco Cloud Observability platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/apis.yml)

## Tags

- APM
- Application Performance Monitoring
- Cisco
- Cloud Observability
- DevOps
- Monitoring
- Observability
- OpenTelemetry

## Timestamps

- **Modified:** 2026-04-19

## APIs

### AppDynamics Controller REST API

The AppDynamics Controller REST API provides programmatic access to the AppDynamics Controller for retrieving application performance data, managing configurations, and automating monitoring workflows. The API uses standard HTTP methods and returns data in XML or JSON format, with the base URI pattern of /controller/rest/. Developers can use it to query application metrics, retrieve transaction snapshots, manage business transactions, and access topology information for monitored applications.

- **Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis)
- **Base URL:** `https://api.example.com`

#### Tags

- Application Performance Monitoring
- Metrics
- Monitoring
- Observability
- Snapshots

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis)
- [OpenAPI](openapi/appdynamics-controller-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-controller-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-controller-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AppDynamics Metric and Snapshot API

The AppDynamics Metric and Snapshot API allows developers to retrieve metric data and transaction snapshots from monitored applications. It supports configurable time ranges, data aggregation through rollup parameters, and access to various metric types including response times, error rates, and call volumes. Developers can retrieve request snapshots for detailed transaction analysis and configure metric retention periods to control how long performance data is stored.

- **Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api)
- **Base URL:** `https://api.example.com`

#### Tags

- Metrics
- Monitoring
- Performance Data
- Snapshots
- Time Series

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api)
- [OpenAPI](openapi/appdynamics-metric-and-snapshot-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-metric-and-snapshot-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-metric-and-snapshot-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AppDynamics Alert and Respond API

The AppDynamics Alert and Respond API enables programmatic management of health rules, policies, and actions within the AppDynamics Controller. Developers can create, update, and delete health rules that define performance thresholds, configure alerting policies that determine how violations are handled, and set up automated response actions. This API is essential for automating incident response workflows and integrating AppDynamics alerting with external notification and ticketing systems.

- **Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- **Base URL:** `https://api.example.com`

#### Tags

- Alerts
- Health Rules
- Incident Response
- Monitoring
- Notifications

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-alert-and-respond-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-alert-and-respond-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-alert-and-respond-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AppDynamics Configuration API

The AppDynamics Configuration API provides endpoints for managing Controller configuration settings programmatically. It includes Configuration Import and Export capabilities that allow administrators to back up, restore, and migrate application configurations between Controller instances. Developers can automate the provisioning and management of application monitoring configurations, business transaction detection rules, and other Controller settings through this API.

- **Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- **Base URL:** `https://api.example.com`

#### Tags

- Administration
- Configuration
- Export
- Import
- Management

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-configuration-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-configuration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-configuration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AppDynamics Analytics Events API

The AppDynamics Analytics Events API allows developers to send custom analytics events from external data sources to the AppDynamics Events Service. This API supports creating custom event schemas, publishing event data, and querying stored events using the AppDynamics Analytics Query Language (ADQL). It enables organizations to correlate application performance data with custom business metrics and external data sources for deeper operational and business intelligence insights.

- **Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- **Base URL:** `https://api.example.com`

#### Tags

- Analytics
- Business Intelligence
- Custom Data
- Events
- Observability

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-analytics-events-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-analytics-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-analytics-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AppDynamics Database Agent API

The AppDynamics Database Agent API provides HTTP endpoints for managing Database Monitoring database Collectors. Developers can programmatically create, retrieve, update, and delete database collectors that monitor the performance and availability of database instances. This API enables automation of database monitoring setup and management, making it possible to scale database visibility across large environments without manual configuration through the Controller UI.

- **Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- **Base URL:** `https://api.example.com`

#### Tags

- Collectors
- Database
- Database Performance
- Monitoring

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-database-agent-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-database-agent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-database-agent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AppDynamics Machine Agent API

The AppDynamics Machine Agent API provides HTTP endpoints available at the machine agent for uploading custom metrics to the AppDynamics Controller. Developers can use this API to report custom infrastructure metrics, hardware metrics, and other machine-level data points that are not captured by the default agent instrumentation. This enables organizations to extend their monitoring coverage to include custom system-level metrics and integrate data from third-party monitoring tools.

- **Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- **Base URL:** `https://api.example.com`

#### Tags

- Custom Metrics
- Infrastructure
- Metrics
- Server Monitoring

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-machine-agent-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-machine-agent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-machine-agent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Cloud Observability API

The Cisco Cloud Observability API is the next-generation cloud-native platform for AppDynamics, available through the Cisco DevNet developer portal. It provides REST APIs for managing cloud connections, configuring health rules, running analytics queries, and managing application principals. The API supports connections to Amazon Web Services, Microsoft Azure, and Google Cloud Platform, enabling automated cloud monitoring setup and management at scale through OpenAPI-documented endpoints.

- **Human URL:** [https://developer.cisco.com/docs/appdynamics/](https://developer.cisco.com/docs/appdynamics/)
- **Base URL:** `https://api.example.com`

#### Tags

- AWS
- Azure
- Cloud
- Connections
- GCP
- Observability

#### Properties

- [Documentation](https://developer.cisco.com/docs/appdynamics/)
- [OpenAPI](openapi/appdynamics-cloud-observability-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-cloud-observability-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-cloud-observability-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AppDynamics OAuth Authentication API

The AppDynamics OAuth Authentication API enables developers to generate short-lived access tokens using the OAuth 2.0 Client Credentials Grant flow. API clients can request access tokens to authenticate against AppDynamics APIs securely without using long-lived credentials. This API is used in conjunction with the Cisco Observability Platform to manage API client credentials and control access to the various AppDynamics platform services and endpoints.

- **Human URL:** [https://developer.cisco.com/docs/appdynamics/authentication/](https://developer.cisco.com/docs/appdynamics/authentication/)
- **Base URL:** `https://api.example.com`

#### Tags

- Access Tokens
- Authentication
- OAuth
- Security

#### Properties

- [Documentation](https://developer.cisco.com/docs/appdynamics/authentication/)
- [OpenAPI](openapi/appdynamics-authentication-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/appdynamics-authentication-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/appdynamics-authentication-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/appdynamics)
- [JSON-LD](json-ld/appdynamics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/appdynamics-application-model-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/appdynamics-health-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/appdynamics-database-collector-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/appdynamics-analytics-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Documentation](https://docs.appdynamics.com/appd/24.x/24.3/en/extend-cisco-appdynamics/cisco-appdynamics-apis)
- [Developer Portal](https://developer.cisco.com/site/appdynamics/)
- [Getting Started](https://developer.cisco.com/docs/appdynamics/)
- [GitHub Organization](https://github.com/Appdynamics)
- [Pricing](https://www.appdynamics.com/pricing/)
- [Support](https://www.cisco.com/c/en/us/support/index.html)
- [JSON Structure](json-structure/appdynamics-application-model-structure.json)
- [JSON Structure](json-structure/appdynamics-health-rule-structure.json)
- [JSON Structure](json-structure/appdynamics-database-collector-structure.json)
- [JSON Structure](json-structure/appdynamics-analytics-event-structure.json)
- [Example](examples/appdynamics-application-model-example.json)
- [Example](examples/appdynamics-health-rule-example.json)
- [Example](examples/appdynamics-database-collector-example.json)
- [Example](examples/appdynamics-analytics-event-example.json)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
