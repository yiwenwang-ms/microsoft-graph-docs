---
title: "extensionProperty resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# extensionProperty resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [directoryObject](../resources/directoryobject.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List extensionProperties](../api/extensionproperty-list.md)|[extensionProperty](../resources/extensionproperty.md) collection|Get a list of the [extensionProperty](../resources/extensionproperty.md) objects and their properties.|
|[Create extensionProperty](../api/extensionproperty-create.md)|[extensionProperty](../resources/extensionproperty.md)|Create a new [extensionProperty](../resources/extensionproperty.md) object.|
|[Get extensionProperty](../api/extensionproperty-get.md)|[extensionProperty](../resources/extensionproperty.md)|Read the properties and relationships of an [extensionProperty](../resources/extensionproperty.md) object.|
|[Update extensionProperty](../api/extensionproperty-update.md)|[extensionProperty](../resources/extensionproperty.md)|Update the properties of an [extensionProperty](../resources/extensionproperty.md) object.|
|[Delete extensionProperty](../api/extensionproperty-delete.md)|None|Deletes an [extensionProperty](../resources/extensionproperty.md) object.|
|[checkMemberGroups](../api/extensionproperty-checkmembergroups.md)|String collection|**TODO: Add Description**|
|[checkMemberObjects](../api/extensionproperty-checkmemberobjects.md)|String collection|**TODO: Add Description**|
|[getMemberGroups](../api/extensionproperty-getmembergroups.md)|String collection|**TODO: Add Description**|
|[getMemberObjects](../api/extensionproperty-getmemberobjects.md)|String collection|**TODO: Add Description**|
|[restore](../api/extensionproperty-restore.md)|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|appDisplayName|String|**TODO: Add Description**|
|dataType|String|**TODO: Add Description**|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|isSyncedFromOnPremises|Boolean|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|targetObjects|String collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.extensionProperty",
  "baseType": "Microsoft.DirectoryServices.directoryObject",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.extensionProperty",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)",
  "appDisplayName": "String",
  "name": "String",
  "dataType": "String",
  "isSyncedFromOnPremises": "Boolean",
  "targetObjects": [
    "String"
  ]
}
```

