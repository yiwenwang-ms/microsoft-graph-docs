---
title: "educationSynchronizationCustomization resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationSynchronizationCustomization resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowDisplayNameUpdate|Boolean|**TODO: Add Description**|
|isSyncDeferred|Boolean|**TODO: Add Description**|
|optionalPropertiesToSync|String collection|**TODO: Add Description**|
|synchronizationStartDate|DateTimeOffset|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.educationSynchronizationCustomization"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationSynchronizationCustomization",
  "optionalPropertiesToSync": [
    "String"
  ],
  "synchronizationStartDate": "String (timestamp)",
  "isSyncDeferred": "Boolean",
  "allowDisplayNameUpdate": "Boolean"
}
```

