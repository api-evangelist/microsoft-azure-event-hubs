---
title: "Update WCF Relay applications to use TLS 1.2 or later"
url: "https://techcommunity.microsoft.com/t5/messaging-on-azure-blog/update-wcf-relay-applications-to-use-tls-1-2-or-later/ba-p/4544418"
date: "2026-08-05"
author: "EldertGrootenboer"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=MessagingonAzureBlog"
---
WCF Relay listeners that still negotiate TLS 1.0 can fail to connect through Azure Relay. The symptom appears on the sender, which connected successfully before and now fails every call with System.ServiceModel.EndpointNotFoundException: no connected listeners accepted the connection within timeout . If you run a WCF Relay listener on the .NET Framework, and especially one built against an older version of the WindowsAzure.ServiceBus package or Microsoft.ServiceBus.dll , it is worth checking how it negotiates TLS.
