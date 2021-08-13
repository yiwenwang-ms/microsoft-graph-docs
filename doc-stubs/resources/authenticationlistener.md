---
title: "authenticationListener resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# authenticationListener resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**
This is an abstract type.

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List authenticationListeners](../api/authenticationlistener-list.md)|[authenticationListener](../resources/authenticationlistener.md) collection|Get a list of the [authenticationListener](../resources/authenticationlistener.md) objects and their properties.|
|[Create authenticationListener](../api/authenticationlistener-create.md)|[authenticationListener](../resources/authenticationlistener.md)|Create a new [authenticationListener](../resources/authenticationlistener.md) object.|
|[Get authenticationListener](../api/authenticationlistener-get.md)|[authenticationListener](../resources/authenticationlistener.md)|Read the properties and relationships of an [authenticationListener](../resources/authenticationlistener.md) object.|
|[Update authenticationListener](../api/authenticationlistener-update.md)|[authenticationListener](../resources/authenticationlistener.md)|Update the properties of an [authenticationListener](../resources/authenticationlistener.md) object.|
|[Delete authenticationListener](../api/authenticationlistener-delete.md)|None|Deletes an [authenticationListener](../resources/authenticationlistener.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|priority|Int32|**TODO: Add Description**|
|sourceFilter|[authenticationSourceFilter](../resources/authenticationsourcefilter.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.authenticationListener",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.authenticationListener",
  "id": "String (identifier)",
  "priority": "Integer",
  "sourceFilter": {
    "@odata.type": "microsoft.graph.authenticationSourceFilter"
  }
}
```

