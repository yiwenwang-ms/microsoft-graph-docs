---
title: "itemInsightsSettings resource type"
description: "Represents privacy settings for itemInsights."
ms.localizationpriority: medium
author: "simonhult"
ms.prod: "insights"
doc_type: resourcePageType
---

# itemInsightsSettings resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents privacy settings for [itemInsights](iteminsights.md) and privacy setting for [meeting hours insights](https://support.microsoft.com/en-us/office/update-your-meeting-hours-using-the-profile-card-0613d113-d7c1-4faa-bb11-c8ba30a78ef1)
. Use this API to disable/enable calculation and visibility of item insights and meeting hours insights. 

- Item insights: Calculates relationship between users and items such as documents or sites in Microsoft 365.  
- Meeting hours insights: Calculates a person's calendar meeting hours based on activities in Word, Excel, PowerPoint, email, and Outlook calendar in Microsoft 365.

Use the [userInsightsSettings](userinsightssettings.md) resource to disable/enable calculation and visibility of item insights and meeting hours insights of a user.

## Methods

| Method       | Return Type | Description |
|:-------------------------------------------------------------|:----------------------------------------------|:-----------------------------------------------------------------|
| [Get](../api/iteminsightssettings-get.md)| [itemInsightsSettings](iteminsightssettings.md) | Read the properties of an **itemInsightsSettings** object. |
| [Update](../api/iteminsightssettings-update.md)| [itemInsightsSettings](iteminsightssettings.md) | Update an **itemInsightsSettings** object.|


## Properties
| Property   | Type|Description|
|:---------------|:--------|:----------|
|isEnabledInOrganization|Boolean| `true` if organization item insights are enabled; `false` if organization item insights are disabled for all users without exceptions. Default is `true`. Optional.|
|disabledForGroup|String| The ID of an Azure AD group, of which the members' item insights are disabled. Default is `empty`. Optional.|

## JSON representation

Here is a JSON representation of the resource
<!-- {
  "blockType": "resource",
  "optionalProperties": [],
  "@odata.type": "microsoft.graph.itemInsightsSettings"
}-->

```json
{
  "isEnabledInOrganization": "Boolean",
  "disabledForGroup": "String"
}
```


