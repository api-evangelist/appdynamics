# AppDynamics (appdynamics)
AppDynamics, now part of Cisco, is an application performance monitoring and observability platform that helps organizations monitor, troubleshoot, and optimize application performance. Their developer platform offers a comprehensive set of REST APIs for managing controller configurations, retrieving performance metrics and transaction snapshots, automating alerting workflows, and integrating with cloud observability through the Cisco DevNet portal.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Application Performance Monitoring, Observability, Metrics, Analytics, Cloud, Monitoring

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### AppDynamics Controller REST API
The AppDynamics Controller REST API provides programmatic access to the AppDynamics Controller for retrieving application performance data, managing configurations, and automating monitoring workflows. The API uses standard HTTP methods and returns data in XML or JSON format, with the base URI pattern of /controller/rest/. Developers can use it to query application metrics, retrieve transaction snapshots, manage business transactions, and access topology information for monitored applications.

**Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis)


#### Tags:

 - Application Performance Monitoring, Metrics, Snapshots, Observability, Monitoring

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis)
- [OpenAPI](openapi/appdynamics-controller-rest-api-openapi.yml)

### AppDynamics Metric and Snapshot API
The AppDynamics Metric and Snapshot API allows developers to retrieve metric data and transaction snapshots from monitored applications. It supports configurable time ranges, data aggregation through rollup parameters, and access to various metric types including response times, error rates, and call volumes. Developers can retrieve request snapshots for detailed transaction analysis and configure metric retention periods to control how long performance data is stored.

**Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api)


#### Tags:

 - Metrics, Snapshots, Performance Data, Time Series, Monitoring

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api)
- [OpenAPI](openapi/appdynamics-metric-and-snapshot-api-openapi.yml)

### AppDynamics Alert and Respond API
The AppDynamics Alert and Respond API enables programmatic management of health rules, policies, and actions within the AppDynamics Controller. Developers can create, update, and delete health rules that define performance thresholds, configure alerting policies that determine how violations are handled, and set up automated response actions. This API is essential for automating incident response workflows and integrating AppDynamics alerting with external notification and ticketing systems.

**Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)


#### Tags:

 - Alerts, Health Rules, Notifications, Incident Response, Monitoring

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-alert-and-respond-api-openapi.yml)

### AppDynamics Configuration API
The AppDynamics Configuration API provides endpoints for managing Controller configuration settings programmatically. It includes Configuration Import and Export capabilities that allow administrators to back up, restore, and migrate application configurations between Controller instances. Developers can automate the provisioning and management of application monitoring configurations, business transaction detection rules, and other Controller settings through this API.

**Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)


#### Tags:

 - Configuration, Import, Export, Administration, Management

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-configuration-api-openapi.yml)

### AppDynamics Analytics Events API
The AppDynamics Analytics Events API allows developers to send custom analytics events from external data sources to the AppDynamics Events Service. This API supports creating custom event schemas, publishing event data, and querying stored events using the AppDynamics Analytics Query Language (ADQL). It enables organizations to correlate application performance data with custom business metrics and external data sources for deeper operational and business intelligence insights.

**Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)


#### Tags:

 - Analytics, Events, Custom Data, Business Intelligence, Observability

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-analytics-events-api-openapi.yml)

### AppDynamics Database Agent API
The AppDynamics Database Agent API provides HTTP endpoints for managing Database Monitoring database Collectors. Developers can programmatically create, retrieve, update, and delete database collectors that monitor the performance and availability of database instances. This API enables automation of database monitoring setup and management, making it possible to scale database visibility across large environments without manual configuration through the Controller UI.

**Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)


#### Tags:

 - Database, Monitoring, Collectors, Database Performance

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-database-agent-api-openapi.yml)

### AppDynamics Machine Agent API
The AppDynamics Machine Agent API provides HTTP endpoints available at the machine agent for uploading custom metrics to the AppDynamics Controller. Developers can use this API to report custom infrastructure metrics, hardware metrics, and other machine-level data points that are not captured by the default agent instrumentation. This enables organizations to extend their monitoring coverage to include custom system-level metrics and integrate data from third-party monitoring tools.

**Human URL:** [https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)


#### Tags:

 - Infrastructure, Metrics, Custom Metrics, Server Monitoring

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [OpenAPI](openapi/appdynamics-machine-agent-api-openapi.yml)

### Cisco Cloud Observability API
The Cisco Cloud Observability API is the next-generation cloud-native platform for AppDynamics, available through the Cisco DevNet developer portal. It provides REST APIs for managing cloud connections, configuring health rules, running analytics queries, and managing application principals. The API supports connections to Amazon Web Services, Microsoft Azure, and Google Cloud Platform, enabling automated cloud monitoring setup and management at scale through OpenAPI-documented endpoints.

**Human URL:** [https://developer.cisco.com/docs/appdynamics/](https://developer.cisco.com/docs/appdynamics/)


#### Tags:

 - Cloud, Observability, Connections, AWS, Azure, GCP

#### Properties

- [Documentation](https://developer.cisco.com/docs/appdynamics/)
- [OpenAPI](openapi/appdynamics-cloud-observability-api-openapi.yml)

### AppDynamics OAuth Authentication API
The AppDynamics OAuth Authentication API enables developers to generate short-lived access tokens using the OAuth 2.0 Client Credentials Grant flow. API clients can request access tokens to authenticate against AppDynamics APIs securely without using long-lived credentials. This API is used in conjunction with the Cisco Observability Platform to manage API client credentials and control access to the various AppDynamics platform services and endpoints.

**Human URL:** [https://developer.cisco.com/docs/appdynamics/authentication/](https://developer.cisco.com/docs/appdynamics/authentication/)


#### Tags:

 - Authentication, OAuth, Security, Access Tokens

#### Properties

- [Documentation](https://developer.cisco.com/docs/appdynamics/authentication/)
- [OpenAPI](openapi/appdynamics-authentication-api-openapi.yml)

## Common Properties

- [Portal](https://developer.cisco.com/docs/appdynamics/)
- [Documentation](https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis)
- [Website](https://www.appdynamics.com)
- [PrivacyPolicy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [TermsOfService](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [Support](https://www.appdynamics.com/support)
- [Blog](https://www.appdynamics.com/blog)
- [Login](https://accounts.appdynamics.com/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
