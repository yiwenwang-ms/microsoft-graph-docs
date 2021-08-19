---
title: "directoryObject: checkMemberObjects"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# directoryObject: checkMemberObjects
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
POST /me/manager/checkMemberObjects
POST /users/{usersId}/manager/checkMemberObjects
POST /contacts/{contactsId}/manager/checkMemberObjects
POST /me/memberOf/{directoryObjectId}/checkMemberObjects
POST /groups/{groupsId}/createdOnBehalfOf/checkMemberObjects
POST /me/ownedDevices/{directoryObjectId}/checkMemberObjects
POST /me/ownedObjects/{directoryObjectId}/checkMemberObjects
POST /me/directReports/{directoryObjectId}/checkMemberObjects
POST /directoryObjects/{directoryObjectsId}/checkMemberObjects
POST /me/createdObjects/{directoryObjectId}/checkMemberObjects
POST /stsPolicy/appliesTo/{directoryObjectId}/checkMemberObjects
POST /me/transitiveReports/{directoryObjectId}/checkMemberObjects
POST /me/registeredDevices/{directoryObjectId}/checkMemberObjects
POST /me/transitiveMemberOf/{directoryObjectId}/checkMemberObjects
POST /directory/deletedItems/{directoryObjectId}/checkMemberObjects
POST /applications/{applicationsId}/createdOnBehalfOf/checkMemberObjects
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
|ids|String collection|**TODO: Add Description**|



## Response

If successful, this action returns a `200 OK` response code and a String collection in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "directoryobject_checkmemberobjects"
}
-->
``` http
POST https://graph.microsoft.com/beta/me/manager/checkMemberObjects
Content-Type: application/json
Content-length: 35

{
  "ids": [
    "String"
  ]
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(Edm.String)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    "String"
  ]
}
```

