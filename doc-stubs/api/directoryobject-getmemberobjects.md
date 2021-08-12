---
title: "directoryObject: getMemberObjects"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# directoryObject: getMemberObjects
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
POST /me/manager/getMemberObjects
POST /users/{usersId}/manager/getMemberObjects
POST /contacts/{contactsId}/manager/getMemberObjects
POST /me/memberOf/{directoryObjectId}/getMemberObjects
POST /groups/{groupsId}/createdOnBehalfOf/getMemberObjects
POST /me/ownedDevices/{directoryObjectId}/getMemberObjects
POST /me/ownedObjects/{directoryObjectId}/getMemberObjects
POST /me/directReports/{directoryObjectId}/getMemberObjects
POST /directoryObjects/{directoryObjectsId}/getMemberObjects
POST /me/createdObjects/{directoryObjectId}/getMemberObjects
POST /stsPolicy/appliesTo/{directoryObjectId}/getMemberObjects
POST /me/transitiveReports/{directoryObjectId}/getMemberObjects
POST /me/registeredDevices/{directoryObjectId}/getMemberObjects
POST /me/transitiveMemberOf/{directoryObjectId}/getMemberObjects
POST /directory/deletedItems/{directoryObjectId}/getMemberObjects
POST /applications/{applicationsId}/createdOnBehalfOf/getMemberObjects
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
|securityEnabledOnly|Boolean|**TODO: Add Description**|



## Response

If successful, this action returns a `200 OK` response code and a String collection in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "directoryobject_getmemberobjects"
}
-->
``` http
POST https://graph.microsoft.com/beta/me/manager/getMemberObjects
Content-Type: application/json
Content-length: 40

{
  "securityEnabledOnly": "Boolean"
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

