# Azure Event Hubs (microsoft-azure-event-hubs)
Azure Event Hubs is a big data streaming platform and event ingestion service that can receive and process millions of events per second. It provides a distributed stream processing platform with low latency and seamless integration with Azure data and analytics services.

**URL:** [Visit APIs.json URL](https://azure.microsoft.com/en-us/services/event-hubs/)

## Tags:

 - Big Data, Event Streaming, IoT, Message Ingestion, Real-Time Processing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Azure Event Hubs REST API
REST API for managing Event Hubs namespaces, event hubs, consumer groups, and sending/receiving events.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/eventhub/](https://learn.microsoft.com/en-us/rest/api/eventhub/)

**Base URL:** https://management.azure.com

#### Tags:

 - Events, Management, Streaming

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/eventhub/)
- [OpenAPI](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/resource-manager)
- [Swagger](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/eventhub/resource-manager/Microsoft.EventHub/stable/2021-11-01/eventhub.json)
- [OpenAPI](openapi/azure-event-hubs-management-openapi.yml)

### Azure Event Hubs Data Plane API
API for sending and receiving events from Event Hubs.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest](https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest)

**Base URL:** https://{namespace}.servicebus.windows.net

#### Tags:

 - Data Plane, Receive Events, Send Events

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest)
- [OpenAPI](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/data-plane)
- [OpenAPI](openapi/azure-event-hubs-data-plane-openapi.yml)

### Azure Event Hubs Messaging API
Event-driven messaging API for publishing and consuming events via AMQP 1.0, Kafka, and HTTPS protocols. Supports partitioned event streams, consumer groups, and publisher policies.

**Human URL:** [https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features)

**Base URL:** https://{namespace}.servicebus.windows.net

#### Tags:

 - AMQP, AsyncAPI, Event Streaming, Kafka, Messaging

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features)
- [AsyncAPI](asyncapi/azure-event-hubs-messaging-asyncapi.yml)

### Azure Event Hubs SDK
Client libraries for various programming languages to interact with Event Hubs.

**Human URL:** [https://learn.microsoft.com/en-us/azure/event-hubs/sdks](https://learn.microsoft.com/en-us/azure/event-hubs/sdks)

**Base URL:** https://{namespace}.servicebus.windows.net

#### Tags:

 - Client Library, SDK

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/event-hubs/sdks)
- [.NET SDK](https://www.nuget.org/packages/Azure.Messaging.EventHubs/)
- [Java SDK](https://mvnrepository.com/artifact/com.azure/azure-messaging-eventhubs)
- [Python SDK](https://pypi.org/project/azure-eventhub/)
- [JavaScript SDK](https://www.npmjs.com/package/@azure/event-hubs)
- [GitHub](https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/eventhub)

## Common Properties

- [Portal](https://portal.azure.com/#blade/HubsExtension/BrowseResource/resourceType/Microsoft.EventHub%2Fnamespaces)
- [Getting Started](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quickstart-portal)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/event-hubs/)
- [Service Level Agreement](https://azure.microsoft.com/en-us/support/legal/sla/event-hubs/)
- [Authentication](https://learn.microsoft.com/en-us/azure/event-hubs/authenticate-application)
- [Best Practices](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-best-practices)
- [Samples](https://github.com/Azure/azure-event-hubs/tree/master/samples)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Status](https://status.azure.com/)
- [Blog](https://techcommunity.microsoft.com/t5/messaging-on-azure-and-net/bg-p/MessagingonAzureBlog)
- [Documentation](https://learn.microsoft.com/en-us/azure/event-hubs/)
- [Quotas](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quotas)
- [Security](https://learn.microsoft.com/en-us/azure/event-hubs/network-security)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Event Hubs Management](openapi/azure-event-hubs-management-openapi.yml)
- [Azure Event Hubs Data Plane](openapi/azure-event-hubs-data-plane-openapi.yml)

### AsyncAPI

- [Azure Event Hubs Messaging](asyncapi/azure-event-hubs-messaging-asyncapi.yml)

### JSON Schema

- [Azure Event Hubs Namespace](json-schema/azure-event-hubs-namespace.json)
- [Azure Event Hubs Event Hub](json-schema/azure-event-hubs-eventhub.json)
- [Azure Event Hubs Consumer Group](json-schema/azure-event-hubs-consumer-group.json)
- [Azure Event Hubs Event Data](json-schema/azure-event-hubs-event-data.json)
- [Azure Event Hubs Schema Group](json-schema/azure-event-hubs-schema-group.json)

### JSON-LD

- [Azure Event Hubs Context](json-ld/azure-event-hubs-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
