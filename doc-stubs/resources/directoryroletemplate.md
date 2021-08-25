---
title: "directoryRoleTemplate resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# directoryRoleTemplate resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [directoryObject](../resources/directoryobject.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List directoryRoleTemplates](../api/directoryroletemplate-list.md)|[directoryRoleTemplate](../resources/directoryroletemplate.md) collection|Get a list of the [directoryRoleTemplate](../resources/directoryroletemplate.md) objects and their properties.|
|[Create directoryRoleTemplate](../api/directoryroletemplate-post-directoryroletemplates.md)|[directoryRoleTemplate](../resources/directoryroletemplate.md)|Create a new [directoryRoleTemplate](../resources/directoryroletemplate.md) object.|
|[Get directoryRoleTemplate](../api/directoryroletemplate-get.md)|[directoryRoleTemplate](../resources/directoryroletemplate.md)|Read the properties and relationships of a [directoryRoleTemplate](../resources/directoryroletemplate.md) object.|
|[Update directoryRoleTemplate](../api/directoryroletemplate-update.md)|[directoryRoleTemplate](../resources/directoryroletemplate.md)|Update the properties of a [directoryRoleTemplate](../resources/directoryroletemplate.md) object.|
|[Delete directoryRoleTemplate](../api/directoryroletemplate-delete.md)|None|Deletes a [directoryRoleTemplate](../resources/directoryroletemplate.md) object.|
|[checkMemberGroups](../api/directoryroletemplate-checkmembergroups.md)|String collection|**TODO: Add Description**|
|[checkMemberObjects](../api/directoryroletemplate-checkmemberobjects.md)|String collection|**TODO: Add Description**|
|[getMemberGroups](../api/directoryroletemplate-getmembergroups.md)|String collection|**TODO: Add Description**|
|[getMemberObjects](../api/directoryroletemplate-getmemberobjects.md)|String collection|**TODO: Add Description**|
|[restore](../api/directoryroletemplate-restore.md)|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.directoryRoleTemplate",
  "baseType": "Microsoft.DirectoryServices.directoryObject",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.directoryRoleTemplate",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String"
}
```

