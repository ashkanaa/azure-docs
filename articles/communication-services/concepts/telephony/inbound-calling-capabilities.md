---
title: Inbound calling capabilities - Azure Communication Services
description: Enable inbound PSTN and direct routing calling for different endpoints in Azure Communication Services.
author: boris-bazilevskiy
manager: rcole
services: azure-communication-services

ms.author: krkutser
ms.date: 07/29/2022
ms.topic: conceptual
ms.service: azure-communication-services
ms.subservice: pstn
---

# Enable inbound telephony calling for Azure Communication Services.

Inbound PSTN calling is currently supported in GA for Dynamics Omnichannel. You can use phone numbers [provided by Microsoft](./telephony-concept.md#voice-calling-pstn) and phone numbers supplied by [direct routing](./telephony-concept.md#azure-direct-routing).

**Inbound calling with Dynamics 365 Omnichannel (OC)**

Supported in General Availability, to set up inbound calling for Dynamics 365 OC with direct routing or Voice Calling (PSTN) follow [these instructions](/dynamics365/customer-service/voice-channel-inbound-calling).

**Inbound calling with ACS Call Automation SDK**

Call Automation enables you to build custom calling workflows within your applications to optimize business processes and boost customer satisfaction. The library supports managing incoming calls to the phone numbers acquired from Communication Services and incoming calls via Direct Routing. You can also use Call Automation to place outbound calls from the phone numbers owned by your resource, among other capabilities.   

Learn more about [Call Automation](../voice-video-calling/call-automation.md), currently available in public preview.

**Inbound calling with Azure Bot Framework**

Customers participating in Azure Bot Framework Telephony Channel preview can find the [instructions here](/azure/bot-service/bot-service-channel-connect-telephony)

**Inbound calling with Power Virtual Agents**

*Coming soon*
