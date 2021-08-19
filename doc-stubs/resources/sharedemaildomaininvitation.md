---
title: "sharedEmailDomainInvitation resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# sharedEmailDomainInvitation resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List sharedEmailDomainInvitations](../api/sharedemaildomaininvitation-list.md)|[sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) collection|Get a list of the [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) objects and their properties.|
|[Create sharedEmailDomainInvitation](../api/sharedemaildomaininvitation-create.md)|[sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md)|Create a new [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) object.|
|[Get sharedEmailDomainInvitation](../api/sharedemaildomaininvitation-get.md)|[sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md)|Read the properties and relationships of a [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) object.|
|[Update sharedEmailDomainInvitation](../api/sharedemaildomaininvitation-update.md)|[sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md)|Update the properties of a [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) object.|
|[Delete sharedEmailDomainInvitation](../api/sharedemaildomaininvitation-delete.md)|None|Deletes a [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|expiryTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|invitationDomain|String|**TODO: Add Description**|
|invitationStatus|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.sharedEmailDomainInvitation",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.sharedEmailDomainInvitation",
  "id": "String (identifier)",
  "invitationDomain": "String",
  "invitationStatus": "String",
  "expiryTime": "String (timestamp)"
}
```

