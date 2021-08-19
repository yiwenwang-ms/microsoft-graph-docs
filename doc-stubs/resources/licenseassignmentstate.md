---
title: "licenseAssignmentState resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# licenseAssignmentState resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|assignedByGroup|String|**TODO: Add Description**|
|disabledPlans|Guid collection|**TODO: Add Description**|
|error|String|**TODO: Add Description**|
|skuId|Guid|**TODO: Add Description**|
|state|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.licenseAssignmentState"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.licenseAssignmentState",
  "skuId": "Guid",
  "disabledPlans": [
    "Guid"
  ],
  "assignedByGroup": "String",
  "state": "String",
  "error": "String"
}
```

