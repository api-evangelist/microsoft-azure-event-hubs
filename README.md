# Azure Event Hubs (microsoft-azure-event-hubs)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Azure Event Hubs is a big data streaming platform and event ingestion service that can receive and process millions of events per second. It provides a distributed stream processing platform with low latency and seamless integration with Azure data and analytics services.

**APIs.json:** [https://azure.microsoft.com/en-us/services/event-hubs/](https://azure.microsoft.com/en-us/services/event-hubs/)

## Tags

- Big Data
- Event Streaming
- IoT
- Message Ingestion
- Real-Time Processing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Azure Event Hubs REST API

REST API for managing Event Hubs namespaces, event hubs, consumer groups, and sending/receiving events.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/eventhub/](https://learn.microsoft.com/en-us/rest/api/eventhub/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Events
- Management
- Streaming

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/eventhub/)
- [OpenAPI](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/resource-manager) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Swagger](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/eventhub/resource-manager/Microsoft.EventHub/stable/2021-11-01/eventhub.json)
- [OpenAPI](openapi/azure-event-hubs-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-event-hubs-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-event-hubs-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Event Hubs Data Plane API

API for sending and receiving events from Event Hubs.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest](https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest)
- **Base URL:** `https://{namespace}.servicebus.windows.net`

#### Tags

- Data Plane
- Receive Events
- Send Events

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest)
- [OpenAPI](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/data-plane) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-event-hubs-data-plane-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-event-hubs-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-event-hubs-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Event Hubs Messaging API

Event-driven messaging API for publishing and consuming events via AMQP 1.0, Kafka, and HTTPS protocols. Supports partitioned event streams, consumer groups, and publisher policies.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features)
- **Base URL:** `https://{namespace}.servicebus.windows.net`

#### Tags

- AMQP
- AsyncAPI
- Event Streaming
- Kafka
- Messaging

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features)
- [AsyncAPI](asyncapi/azure-event-hubs-messaging-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/azure-event-hubs-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-event-hubs-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-event-hubs-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-event-hubs-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Event Hubs SDK

Client libraries for various programming languages to interact with Event Hubs.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/event-hubs/sdks](https://learn.microsoft.com/en-us/azure/event-hubs/sdks)
- **Base URL:** `https://{namespace}.servicebus.windows.net`

#### Tags

- Client Library
- SDK

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/event-hubs/sdks)
- [. N E T  S D K](https://www.nuget.org/packages/Azure.Messaging.EventHubs/)
- [Java  S D K](https://mvnrepository.com/artifact/com.azure/azure-messaging-eventhubs)
- [Python  S D K](https://pypi.org/project/azure-eventhub/)
- [Java Script  S D K](https://www.npmjs.com/package/@azure/event-hubs)
- [Git Hub](https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/eventhub)
- [Postman Collection](collections/azure-event-hubs-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-event-hubs-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-event-hubs-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-event-hubs-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://portal.azure.com/#blade/HubsExtension/BrowseResource/resourceType/Microsoft.EventHub%2Fnamespaces)
- [Getting Started](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quickstart-portal)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/event-hubs/)
- [Service Level Agreement](https://azure.microsoft.com/en-us/support/legal/sla/event-hubs/)
- [Authentication](https://learn.microsoft.com/en-us/azure/event-hubs/authenticate-application)
- [Best  Practices](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-best-practices)
- [Samples](https://github.com/Azure/azure-event-hubs/tree/master/samples)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Status Page](https://status.azure.com/)
- [Blog](https://techcommunity.microsoft.com/t5/messaging-on-azure-and-net/bg-p/MessagingonAzureBlog)
- [Documentation](https://learn.microsoft.com/en-us/azure/event-hubs/)
- [Quotas](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quotas)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [S D Ks](https://learn.microsoft.com/en-us/azure/event-hubs/sdks)
- [GitHub Organization](https://github.com/Azure)
- [Website](https://azure.microsoft.com/en-us/services/event-hubs/)
- [Login](https://portal.azure.com/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)
- [Community](https://learn.microsoft.com/en-us/answers/tags/165/azure-event-hubs/)
- [Security](https://learn.microsoft.com/en-us/azure/event-hubs/network-security)
- [J S O N  Schema](json-schema/azure-event-hubs-namespace.json)
- [J S O N  Schema](json-schema/azure-event-hubs-eventhub.json)
- [J S O N  Schema](json-schema/azure-event-hubs-consumer-group.json)
- [J S O N  Schema](json-schema/azure-event-hubs-event-data.json)
- [J S O N  Schema](json-schema/azure-event-hubs-schema-group.json)
- [J S O N- L D  Context](json-ld/azure-event-hubs-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
