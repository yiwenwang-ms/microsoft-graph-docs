---
title: "educationSynchronizationProfileStatus resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationSynchronizationProfileStatus resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationSynchronizationProfileStatus](../api/educationsynchronizationprofilestatus-list.md)|[educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md) collection|Get a list of the [educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md) objects and their properties.|
|[Create educationSynchronizationProfileStatus](../api/educationsynchronizationprofilestatus-create.md)|[educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md)|Create a new [educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md) object.|
|[Get educationSynchronizationProfileStatus](../api/educationsynchronizationprofilestatus-get.md)|[educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md)|Read the properties and relationships of an [educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md) object.|
|[Update educationSynchronizationProfileStatus](../api/educationsynchronizationprofilestatus-update.md)|[educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md)|Update the properties of an [educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md) object.|
|[Delete educationSynchronizationProfileStatus](../api/educationsynchronizationprofilestatus-delete.md)|None|Deletes an [educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|lastActivityDateTime|DateTimeOffset|**TODO: Add Description**|
|lastSynchronizationDateTime|DateTimeOffset|**TODO: Add Description**|
|status|educationSynchronizationStatus|**TODO: Add Description**. Possible values are: `paused`, `inProgress`, `success`, `error`, `validationError`, `quarantined`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.educationSynchronizationProfileStatus",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationSynchronizationProfileStatus",
  "status": "String",
  "lastSynchronizationDateTime": "String (timestamp)",
  "lastActivityDateTime": "String (timestamp)",
  "id": "String (identifier)"
}
```

