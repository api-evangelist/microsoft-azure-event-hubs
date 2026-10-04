---
title: "What the Azure API Management integration means for Azure Service Bus"
url: "https://techcommunity.microsoft.com/t5/messaging-on-azure-blog/what-the-azure-api-management-integration-means-for-azure/ba-p/4558087"
date: "2026-09-21"
author: "EldertGrootenboer"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=MessagingonAzureBlog"
---
Azure API Management now provides a generally available policy for sending messages to Azure Service Bus. Using the send-service-bus-message policy , an API request can send a message directly to a Service Bus queue or topic. This allows you to put a governed HTTP API in front of an asynchronous messaging solution, without adding an intermediary service just to translate and forward the request.
