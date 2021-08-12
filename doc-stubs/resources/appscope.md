---
title: "appScope resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# appScope resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List appScopes](../api/appscope-list.md)|[appScope](../resources/appscope.md) collection|Get a list of the [appScope](../resources/appscope.md) objects and their properties.|
|[Create appScope](../api/appscope-create.md)|[appScope](../resources/appscope.md)|Create a new [appScope](../resources/appscope.md) object.|
|[Get appScope](../api/appscope-get.md)|[appScope](../resources/appscope.md)|Read the properties and relationships of an [appScope](../resources/appscope.md) object.|
|[Update appScope](../api/appscope-update.md)|[appScope](../resources/appscope.md)|Update the properties of an [appScope](../resources/appscope.md) object.|
|[Delete appScope](../api/appscope-delete.md)|None|Deletes an [appScope](../resources/appscope.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|type|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.appScope",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.appScope",
  "id": "String (identifier)",
  "displayName": "String",
  "type": "String"
}
```

