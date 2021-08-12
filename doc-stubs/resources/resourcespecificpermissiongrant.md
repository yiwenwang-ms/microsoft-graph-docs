---
title: "resourceSpecificPermissionGrant resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# resourceSpecificPermissionGrant resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [directoryObject](../resources/directoryobject.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List resourceSpecificPermissionGrants](../api/resourcespecificpermissiongrant-list.md)|[resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md) collection|Get a list of the [resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md) objects and their properties.|
|[Create resourceSpecificPermissionGrant](../api/resourcespecificpermissiongrant-post-permissiongrants.md)|[resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md)|Create a new [resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md) object.|
|[Get resourceSpecificPermissionGrant](../api/resourcespecificpermissiongrant-get.md)|[resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md)|Read the properties and relationships of a [resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md) object.|
|[Update resourceSpecificPermissionGrant](../api/resourcespecificpermissiongrant-update.md)|[resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md)|Update the properties of a [resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md) object.|
|[Delete resourceSpecificPermissionGrant](../api/resourcespecificpermissiongrant-delete.md)|None|Deletes a [resourceSpecificPermissionGrant](../resources/resourcespecificpermissiongrant.md) object.|
|[checkMemberGroups](../api/resourcespecificpermissiongrant-checkmembergroups.md)|String collection|**TODO: Add Description**|
|[checkMemberObjects](../api/resourcespecificpermissiongrant-checkmemberobjects.md)|String collection|**TODO: Add Description**|
|[getMemberGroups](../api/resourcespecificpermissiongrant-getmembergroups.md)|String collection|**TODO: Add Description**|
|[getMemberObjects](../api/resourcespecificpermissiongrant-getmemberobjects.md)|String collection|**TODO: Add Description**|
|[restore](../api/resourcespecificpermissiongrant-restore.md)|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|clientAppId|String|**TODO: Add Description**|
|clientId|String|**TODO: Add Description**|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|permission|String|**TODO: Add Description**|
|permissionType|String|**TODO: Add Description**|
|resourceAppId|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.resourceSpecificPermissionGrant",
  "baseType": "Microsoft.DirectoryServices.directoryObject",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.resourceSpecificPermissionGrant",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)",
  "clientId": "String",
  "clientAppId": "String",
  "resourceAppId": "String",
  "permissionType": "String",
  "permission": "String"
}
```

