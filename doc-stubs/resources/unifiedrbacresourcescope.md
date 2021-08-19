---
title: "unifiedRbacResourceScope resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# unifiedRbacResourceScope resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List unifiedRbacResourceScopes](../api/unifiedrbacresourcescope-list.md)|[unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md) collection|Get a list of the [unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md) objects and their properties.|
|[Create unifiedRbacResourceScope](../api/unifiedrbacresourcescope-create.md)|[unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md)|Create a new [unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md) object.|
|[Get unifiedRbacResourceScope](../api/unifiedrbacresourcescope-get.md)|[unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md)|Read the properties and relationships of an [unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md) object.|
|[Update unifiedRbacResourceScope](../api/unifiedrbacresourcescope-update.md)|[unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md)|Update the properties of an [unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md) object.|
|[Delete unifiedRbacResourceScope](../api/unifiedrbacresourcescope-delete.md)|None|Deletes an [unifiedRbacResourceScope](../resources/unifiedrbacresourcescope.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|scope|String|**TODO: Add Description**|
|type|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.unifiedRbacResourceScope",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.unifiedRbacResourceScope",
  "id": "String (identifier)",
  "displayName": "String",
  "scope": "String",
  "type": "String"
}
```

