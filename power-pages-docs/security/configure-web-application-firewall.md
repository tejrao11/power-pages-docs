﻿---
title: Configure Web Application Firewall for Power Pages (preview)
description: Learn how to configure Web Application Firewall on Power Pages.
author: nickdoelman
ms.topic: conceptual
ms.custom: 
ms.date: 09/23/2022
ms.author: ndoelman
ms.reviewer: kkendrick
contributors:
    - nickdoelman
    - ProfessorKendrick
---

# Configure Web Application Firewall for Power Pages (preview)

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

Web Application Firewall (WAF) is available for production sites created using Power Pages. In this article, you'll learn about how to enable or disable Web Application Firewall for Power Pages sites.

## Prerequisites

You'll need the following before configuring WAF for your Power Pages website.

- You must be an administrator to configure Web Application Firewall.
- WAF requires Content Delivery Network (CDN) on sites. You must [configure CDN](/power-apps/maker/portals/configure/configure-cdn) before you enable WAF.

## Enable Web Application Firewall for Power Pages sites

1. Open the [Power Platform admin center](https://admin.powerplatform.microsoft.com/environments).

1. Go to **Environments**.  

1. Select the environment where the portal was created.

1. On the **Resources** card, select **Portals**.

    :::image type="content" source="media/configure-web-application-firewall/resources-card-portals-selected.png" alt-text="The Power Platform admin center's Environments page with Portals selected on the Resources card.":::

1. Choose the portal from the available list, and then select **Manage**.

    :::image type="content" source="media/configure-web-application-firewall/manage-portals.png" alt-text="The Power Platform admin center's Environments page with the Manage option emphasized.":::

1. Under **Performance & protection** card, turn on **Enable Web Application Firewall**

    :::image type="content" source="media/configure-web-application-firewall/waf-enabled.gif" alt-text="The Performance and Protection card inside design studio with the Enable Web Application Firewall toggle enabled.":::

## Disable Web Application Firewall for Power Pages sites

1. Open the [Power Platform admin center](https://admin.powerplatform.microsoft.com/environments).

1. Go to **Environments**.  

1. Choose the environment where the portal was created.

1. On the **Resources** card, select **Portals**.

    :::image type="content" source="media/configure-web-application-firewall/resources-card-portals-selected.png" alt-text="The Power Platform admin center's Environments page with Portals selected on the Resources card.":::

1. Choose the portal from the available list, and then select **Manage**.

    :::image type="content" source="media/configure-web-application-firewall/manage-portals.png" alt-text="The Power Platform admin center's Environments page with the Manage option emphasized.":::

1. On the **Performance & Protection** card, turn off **Enable Web Application Firewall**

    :::image type="content" source="media/configure-web-application-firewall/waf-disabled.gif" alt-text="The Enable Web Application Firewall toggle disabled inside design studio.":::

### Next steps

[Web Application Firewall DRS rule groups and rules for Power Pages (preview)](web-application-firewall-rule-groups.md)

### See also

[Web Application Firewall (WAF) for Power Pages (preview)](web-application-firewall.md)