---
title: "oAuth2PermissionGrant resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# oAuth2PermissionGrant resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List oAuth2PermissionGrant](../api/oauth2permissiongrant-list.md)|[oAuth2PermissionGrant](../resources/oauth2permissiongrant.md) collection|Get a list of the [oAuth2PermissionGrant](../resources/oauth2permissiongrant.md) objects and their properties.|
|[Create oAuth2PermissionGrant](../api/oauth2permissiongrant-post-oauth2permissiongrants.md)|[oAuth2PermissionGrant](../resources/oauth2permissiongrant.md)|Create a new [oAuth2PermissionGrant](../resources/oauth2permissiongrant.md) object.|
|[Get oAuth2PermissionGrant](../api/oauth2permissiongrant-get.md)|[oAuth2PermissionGrant](../resources/oauth2permissiongrant.md)|Read the properties and relationships of an [oAuth2PermissionGrant](../resources/oauth2permissiongrant.md) object.|
|[Update oAuth2PermissionGrant](../api/oauth2permissiongrant-update.md)|[oAuth2PermissionGrant](../resources/oauth2permissiongrant.md)|Update the properties of an [oAuth2PermissionGrant](../resources/oauth2permissiongrant.md) object.|
|[Delete oAuth2PermissionGrant](../api/oauth2permissiongrant-delete.md)|None|Deletes an [oAuth2PermissionGrant](../resources/oauth2permissiongrant.md) object.|
|[delta](../api/oauth2permissiongrant-delta.md)|[oAuth2PermissionGrant](../resources/oauth2permissiongrant.md) collection|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|clientId|String|**TODO: Add Description**|
|consentType|String|**TODO: Add Description**|
|expiryTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|principalId|String|**TODO: Add Description**|
|resourceId|String|**TODO: Add Description**|
|scope|String|**TODO: Add Description**|
|startTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.oAuth2PermissionGrant",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.oAuth2PermissionGrant",
  "clientId": "String",
  "consentType": "String",
  "expiryTime": "String (timestamp)",
  "id": "String (identifier)",
  "principalId": "String",
  "resourceId": "String",
  "scope": "String",
  "startTime": "String (timestamp)"
}
```

