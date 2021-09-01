---
title: "Update softwareOathAuthenticationMethod"
description: "Update the properties of a softwareOathAuthenticationMethod object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update softwareOathAuthenticationMethod
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [softwareOathAuthenticationMethod](../resources/softwareoathauthenticationmethod.md) object.

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
PATCH /user/authentication/softwareOathMethods/{softwareOathAuthenticationMethodId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [softwareOathAuthenticationMethod](../resources/softwareoathauthenticationmethod.md) object.

The following table shows the properties that are required when you update the [softwareOathAuthenticationMethod](../resources/softwareoathauthenticationmethod.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [authenticationMethod](../resources/authenticationmethod.md)|
|secretKey|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [softwareOathAuthenticationMethod](../resources/softwareoathauthenticationmethod.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_softwareoathauthenticationmethod"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/user/authentication/softwareOathMethods/{softwareOathAuthenticationMethodId}
Content-Type: application/json
Content-length: 100

{
  "@odata.type": "#microsoft.graph.softwareOathAuthenticationMethod",
  "secretKey": "String"
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
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.softwareOathAuthenticationMethod",
  "id": "6ed8a334-a334-6ed8-34a3-d86e34a3d86e",
  "secretKey": "String"
}
```

