---
title: "identityUserFlowAttribute resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityUserFlowAttribute resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List identityUserFlowAttributes](../api/identityuserflowattribute-list.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md) collection|Get a list of the [identityUserFlowAttribute](../resources/identityuserflowattribute.md) objects and their properties.|
|[Create identityUserFlowAttribute](../api/identityuserflowattribute-create.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Create a new [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Get identityUserFlowAttribute](../api/identityuserflowattribute-get.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Read the properties and relationships of an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Update identityUserFlowAttribute](../api/identityuserflowattribute-update.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Update the properties of an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Delete identityUserFlowAttribute](../api/identityuserflowattribute-delete.md)|None|Deletes an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|dataType|identityUserFlowAttributeDataType|**TODO: Add Description**. Possible values are: `string`, `boolean`, `int64`, `stringCollection`, `dateTime`, `unknownFutureValue`.|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|userFlowAttributeType|identityUserFlowAttributeType|**TODO: Add Description**. Possible values are: `builtIn`, `custom`, `required`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityUserFlowAttribute",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityUserFlowAttribute",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "userFlowAttributeType": "String",
  "dataType": "String"
}
```

