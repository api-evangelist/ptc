# PTC (ptc)

PTC is an industrial technology company providing software platforms and APIs for Industrial IoT (ThingWorx), Product Lifecycle Management (Windchill, Arena), Augmented Reality (Vuforia), Field Service Management (ServiceMax), and industrial connectivity (Kepware) in manufacturing environments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ptc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ptc/refs/heads/main/apis.yml)

## Tags

- Industrial IoT
- PLM
- Augmented Reality
- Field Service Management
- Manufacturing
- IIoT
- CAD
- Digital Transformation

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### ThingWorx REST API

The ThingWorx Industrial IoT platform REST API enables developers to interact with Things, Properties, Services, Events, and Subscriptions via HTTP. Authentication uses an AppKey passed as an HTTP header. Supports building, connecting, and deploying IIoT applications.

- **Human URL:** [https://www.ptc.com/en/products/thingworx](https://www.ptc.com/en/products/thingworx)
- **Base URL:** `https://{your-thingworx-host}/Thingworx`

#### Tags

- Industrial IoT
- IIoT
- REST
- Manufacturing

#### Properties

- [Documentation](https://support.ptc.com/help/thingworx/platform/r9/en/ThingWorx/api_documentation.html)
- [Getting Started](https://community.ptc.com/t5/IoT-Tips/Use-REST-API-to-Access-ThingWorx-Part-1/ta-p/825305)
- [Community](https://community.ptc.com/thingworx-developers-185)
- [Authentication](https://www.ptc.com/en/support/article/CS279189)
- [Graph Q L](graphql/ptc-graphql.md)

### Windchill REST Services

Windchill PLM REST Services provide OData-compliant REST API access to product lifecycle management data including product structures, change management, documents, and configuration management. The API Catalog (Swagger UI) is accessible from a running Windchill instance.

- **Human URL:** [https://www.ptc.com/en/products/windchill](https://www.ptc.com/en/products/windchill)
- **Base URL:** `https://{windchill-host}/WindchillRESTServices`

#### Tags

- PLM
- Product Lifecycle Management
- OData
- REST
- Manufacturing

#### Properties

- [Documentation](https://support.ptc.com/help/windchill_rest_services/r2.0/en/windchill_rest_services/WCCG_RESTAPIsWRS.html)
- [OpenAPI](https://support.ptc.com/help/windchill_rest_services/r1.6/en/windchill_rest_services/API_catalog.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Knowledge Hub](https://www.ptc.com/en/support/article/CS335170)

### Arena PLM REST API

Arena PLM REST API v1 provides full programmatic access to Arena's cloud-based PLM capabilities including Bill of Materials management, change management, quality, and compliance. Full OpenAPI/Swagger documentation available per region with interactive testing.

- **Human URL:** [https://www.ptc.com/en/products/arena](https://www.ptc.com/en/products/arena)
- **Base URL:** `https://api.arenasolutions.com/v1`

#### Tags

- PLM
- Product Lifecycle Management
- BOM
- Change Management
- SaaS

#### Properties

- [Documentation](https://ptc-arena.github.io/arena-dev-help/)
- [OpenAPI](https://api.arenasolutions.com/v1/swagger-ui/index.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Repository](https://github.com/ptc-arena/arena-restapi-doc)
- [Postman Collection](https://github.com/ptc-arena/arena-api-samples/tree/main/postmanSample) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Vuforia Engine Web API

The Vuforia Engine Web API provides HTTPS REST access to cloud-based augmented reality capabilities including Cloud Image Recognition, Cloud Area Targets, and license management for building AR applications across mobile and wearable devices.

- **Human URL:** [https://www.ptc.com/en/products/vuforia](https://www.ptc.com/en/products/vuforia)
- **Base URL:** `https://cloudreco.vuforia.com`

#### Tags

- Augmented Reality
- AR
- Computer Vision
- Cloud Recognition
- Manufacturing

#### Properties

- [Documentation](https://developer.vuforia.com/library/)
- [Developer Portal](https://developer.vuforia.com/home)
- [Web A P I](https://developer.vuforia.com/library/vuforia-engine/web-api/cloud-area-targets-web-api/)
- [Pricing](https://www.ptc.com/en/products/vuforia/vuforia-engine/pricing)
- [SDK](https://developer.vuforia.com/downloads/sdk)

### ServiceMax Max REST API

ServiceMax REST API (Max REST API) enables integration with ServiceMax field service management capabilities including work orders, scheduling, service boards, and field metadata management. Built on the Salesforce platform.

- **Human URL:** [https://www.ptc.com/en/products/servicemax](https://www.ptc.com/en/products/servicemax)
- **Base URL:** `https://{instance}.salesforce.com/services/apexrest/SVMXC`

#### Tags

- Field Service Management
- FSM
- Salesforce
- REST
- Manufacturing

#### Properties

- [Documentation](https://support.ptc.com/help/servicemaxcore/en/articles/service_board/appendix-b-max-rest-api.html)
- [Field Metadata A P I](https://support.ptc.com/help/servicemaxcore/en/articles/service_board/field-metadata-rest-api.html)

### Kepware Configuration REST API

The Kepware KEPServerEX Configuration API is a local REST API that enables programmatic configuration of the industrial connectivity server including channels, devices, tags, and IoT Gateway agents. Accepts and returns JSON-formatted data.

- **Human URL:** [https://www.ptc.com/en/products/kepware](https://www.ptc.com/en/products/kepware)
- **Base URL:** `https://localhost:57412/config/v1`

#### Tags

- Industrial Connectivity
- OPC-UA
- SCADA
- IIoT
- Manufacturing
- Configuration

#### Properties

- [Documentation](https://support.ptc.com/help/kepware/features/en/kepware/features/profilelibrary/ConfigurationAPI.html)
- [Io T Gateway R E S T Docs](https://support.ptc.com/help/kepware/features/en/kepware/features/IOTGATEWAY/working_rest_server.html)
- [Git Hub Org](https://github.com/PTCInc)

## Common Properties

- [Website](https://www.ptc.com)
- [Documentation](https://www.ptc.com/en/support/help/thingworx_doc_resources)
- [Git Hub Org](https://github.com/PTCInc)
- [Git Hub Org](https://github.com/ptc-arena)
- [Git Hub Org](https://github.com/PTC-Education)
- [LinkedIn](https://www.linkedin.com/company/ptc)
- [Blog](https://www.ptc.com/en/blogs/)
- [Community Blog](https://community.ptc.com/t5/Blog/bg-p/BWBlog)
- [Pricing](https://www.ptc.com/en/products/vuforia/vuforia-engine/pricing)
- [Status Page](https://status.ptc.com/)
- [Status Page](https://status.ptc.io/)
- [X (Twitter)](https://x.com/ptc)
- [Social Media](https://www.ptc.com/en/about/social-media)
- [Plans](plans/ptc-plans-pricing.yml)
- [Rate Limits](rate-limits/ptc-rate-limits.yml)
- [Fin Ops](finops/ptc-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
