---
title: "directoryObject: validateProperties"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# directoryObject: validateProperties
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST /me/memberOf/validateProperties
POST /me/ownedDevices/validateProperties
POST /me/ownedObjects/validateProperties
POST /directoryObjects/validateProperties
POST /me/directReports/validateProperties
POST /me/createdObjects/validateProperties
POST /stsPolicy/appliesTo/validateProperties
POST /me/transitiveReports/validateProperties
POST /me/registeredDevices/validateProperties
POST /me/transitiveMemberOf/validateProperties
POST /directory/deletedItems/validateProperties
POST /groups/{groupsId}/owners/validateProperties
POST /users/{usersId}/memberOf/validateProperties
POST /groups/{groupsId}/members/validateProperties
POST /groups/{groupsId}/memberOf/validateProperties
POST /devices/{devicesId}/memberOf/validateProperties
POST /users/{usersId}/ownedDevices/validateProperties
POST /users/{usersId}/ownedObjects/validateProperties
POST /users/{usersId}/directReports/validateProperties
POST /contacts/{contactsId}/memberOf/validateProperties
POST /users/{usersId}/createdObjects/validateProperties
POST /users/{usersId}/transitiveReports/validateProperties
POST /users/{usersId}/registeredDevices/validateProperties
POST /users/{usersId}/transitiveMemberOf/validateProperties
POST /contacts/{contactsId}/directReports/validateProperties
POST /devices/{devicesId}/registeredUsers/validateProperties
POST /groups/{groupsId}/transitiveMembers/validateProperties
POST /applications/{applicationsId}/owners/validateProperties
POST /devices/{devicesId}/registeredOwners/validateProperties
POST /groups/{groupsId}/transitiveMemberOf/validateProperties
POST /applications/{applicationsId}/policies/validateProperties
POST /devices/{devicesId}/transitiveMemberOf/validateProperties
POST /contacts/{contactsId}/transitiveReports/validateProperties
POST /contacts/{contactsId}/transitiveMemberOf/validateProperties
POST /domains/{domainsId}/domainNameReferences/validateProperties
POST /directoryRoles/{directoryRolesId}/members/validateProperties
POST /groups/{groupsId}/membersWithLicenseErrors/validateProperties
POST /servicePrincipals/{servicePrincipalsId}/owners/validateProperties
POST /servicePrincipals/{servicePrincipalsId}/memberOf/validateProperties
POST /servicePrincipals/{servicePrincipalsId}/policies/validateProperties
POST /administrativeUnits/{administrativeUnitsId}/members/validateProperties
POST /servicePrincipals/{servicePrincipalsId}/ownedObjects/validateProperties
POST /servicePrincipals/{servicePrincipalsId}/createdObjects/validateProperties
POST /servicePrincipals/{servicePrincipalsId}/transitiveMemberOf/validateProperties
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply JSON representation of the parameters.

The following table shows the parameters that can be used with this action.

|Parameter|Type|Description|
|:---|:---|:---|
|entityType|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|mailNickname|String|**TODO: Add Description**|
|onBehalfOfUserId|Guid|**TODO: Add Description**|



## Response

If successful, this action returns a `204 No Content` response code.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "directoryobject_validateproperties"
}
-->
``` http
POST https://graph.microsoft.com/beta/me/memberOf/validateProperties
Content-Type: application/json
Content-length: 118

{
  "entityType": "String",
  "displayName": "String",
  "mailNickname": "String",
  "onBehalfOfUserId": "Guid"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 204 No Content
```

