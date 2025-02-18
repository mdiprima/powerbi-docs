---
title: On-premises data gateway
description: This article is an overview of the on-premises data gateway for Power BI. You can use this gateway to work with DirectQuery data sources. You can also use this gateway to refresh cloud datasets with on-premises data.
author: arthiriyer
ms.author: arthii
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-gateways
ms.topic: conceptual
LocalizationGroup: Gateways
ms.date: 05/28/2024
ms.custom: intro-overview
---

# What is an on-premises data gateway?

[!INCLUDE [gateway-rewrite](../includes/gateway-rewrite.md)]

The on-premises data gateway acts as a bridge to provide quick and secure data transfer between on-premises data (data that isn't in the cloud) and several Microsoft cloud services. These cloud services include Power BI, PowerApps, Power Automate, Azure Analysis Services, and Azure Logic Apps. By using a gateway, organizations can keep databases and other data sources on their on-premises networks, yet securely use that on-premises data in cloud services.

## How the gateway works

![Gateway overview](media/service-gateway-onprem/on-premises-data-gateway.png)

For more information on how the gateway works, see [On-premises data gateway architecture](/data-integration/gateway/service-gateway-onprem-indepth).

## Types of gateways

There are three different types of gateways, each for a different scenario:

* **On-premises data gateway**: Allows multiple users to connect to multiple on-premises data sources. With a single gateway installation, you can use an on-premises data gateway with all supported services. This gateway is well-suited to complex scenarios in which multiple people access multiple data sources.

* **On-premises data gateway (personal mode)**: Allows one user to connect to sources and can’t be shared with others. An on-premises data gateway (personal mode) can only be used with Power BI. This gateway is well-suited to scenarios in which you’re the only person who creates reports, and you don't need to share any data sources with others.

* **Virtual network data gateway**: Allows multiple users to connect to multiple data sources secured using virtual networks. No installation is required because it's a Microsoft managed service. This gateway is well-suited to complex scenarios in which multiple people access multiple data sources.

## Use a gateway

There are five main steps for using a gateway:

1. [Download and install the gateway](/data-integration/gateway/service-gateway-install) on a local computer.
1. [Configure the gateway](/data-integration/gateway/service-gateway-app) based on your firewall and other network requirements.
1. [Add gateway admins](/data-integration/gateway/service-gateway-manage) who can also manage and administer other network requirements.
1. [Use the gateway](service-gateway-sql-tutorial.md) to refresh an on-premises data source.
1. [Troubleshoot](service-gateway-onprem-tshoot.md) issues with the gateway.

## Related content

* [Install the on-premises data gateway](/data-integration/gateway/service-gateway-install)
* [Power BI implementation planning: Data gateways](../guidance/powerbi-implementation-planning-data-gateways.md)

More questions? [Try the Power BI Community](https://community.powerbi.com/)
 