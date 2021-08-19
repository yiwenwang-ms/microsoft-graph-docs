---
title: "allowedDataLocation resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# allowedDataLocation resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List allowedDataLocations](../api/alloweddatalocation-list.md)|[allowedDataLocation](../resources/alloweddatalocation.md) collection|Get a list of the [allowedDataLocation](../resources/alloweddatalocation.md) objects and their properties.|
|[Create allowedDataLocation](../api/alloweddatalocation-post-alloweddatalocations.md)|[allowedDataLocation](../resources/alloweddatalocation.md)|Create a new [allowedDataLocation](../resources/alloweddatalocation.md) object.|
|[Get allowedDataLocation](../api/alloweddatalocation-get.md)|[allowedDataLocation](../resources/alloweddatalocation.md)|Read the properties and relationships of an [allowedDataLocation](../resources/alloweddatalocation.md) object.|
|[Update allowedDataLocation](../api/alloweddatalocation-update.md)|[allowedDataLocation](../resources/alloweddatalocation.md)|Update the properties of an [allowedDataLocation](../resources/alloweddatalocation.md) object.|
|[Delete allowedDataLocation](../api/alloweddatalocation-delete.md)|None|Deletes an [allowedDataLocation](../resources/alloweddatalocation.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|appId|String|**TODO: Add Description**|
|domain|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isDefault|Boolean|**TODO: Add Description**|
|location|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.allowedDataLocation",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.allowedDataLocation",
  "id": "String (identifier)",
  "appId": "String",
  "location": "String",
  "isDefault": "Boolean",
  "domain": "String"
}
```

