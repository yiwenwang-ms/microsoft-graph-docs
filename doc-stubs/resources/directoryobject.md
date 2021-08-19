---
title: "directoryObject resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# directoryObject resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List directoryObjects](../api/directoryobject-list.md)|[directoryObject](../resources/directoryobject.md) collection|Get a list of the [directoryObject](../resources/directoryobject.md) objects and their properties.|
|[Create directoryObject](../api/directoryobject-post-directoryobjects.md)|[directoryObject](../resources/directoryobject.md)|Create a new [directoryObject](../resources/directoryobject.md) object.|
|[Get directoryObject](../api/directoryobject-get.md)|[directoryObject](../resources/directoryobject.md)|Read the properties and relationships of a [directoryObject](../resources/directoryobject.md) object.|
|[Update directoryObject](../api/directoryobject-update.md)|[directoryObject](../resources/directoryobject.md)|Update the properties of a [directoryObject](../resources/directoryobject.md) object.|
|[Delete directoryObject](../api/directoryobject-delete.md)|None|Deletes a [directoryObject](../resources/directoryobject.md) object.|
|[getByIds](../api/directoryobject-getbyids.md)|[directoryObject](../resources/directoryobject.md) collection|**TODO: Add Description**|
|[checkMemberGroups](../api/directoryobject-checkmembergroups.md)|String collection|**TODO: Add Description**|
|[checkMemberObjects](../api/directoryobject-checkmemberobjects.md)|String collection|**TODO: Add Description**|
|[getMemberGroups](../api/directoryobject-getmembergroups.md)|String collection|**TODO: Add Description**|
|[getMemberObjects](../api/directoryobject-getmemberobjects.md)|String collection|**TODO: Add Description**|
|[validateProperties](../api/directoryobject-validateproperties.md)|None|**TODO: Add Description**|
|[restore](../api/directoryobject-restore.md)|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|
|[getUserOwnedObjects](../api/directoryobject-getuserownedobjects.md)|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deletedDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.directoryObject",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.directoryObject",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)"
}
```

