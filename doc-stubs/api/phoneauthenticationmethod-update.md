---
title: "Update phoneAuthenticationMethod"
description: "Update the properties of a phoneAuthenticationMethod object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update phoneAuthenticationMethod
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) object.

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
PATCH /user/authentication/phoneMethods/{phoneAuthenticationMethodId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) object.

The following table shows the properties that are required when you update the [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [authenticationMethod](../resources/authenticationmethod.md)|
|phoneNumber|String|**TODO: Add Description**|
|phoneType|authenticationPhoneType|**TODO: Add Description**. The possible values are: `mobile`, `alternateMobile`, `office`, `unknownFutureValue`.|
|smsSignInState|authenticationMethodSignInState|**TODO: Add Description**. The possible values are: `notSupported`, `notAllowedByPolicy`, `notEnabled`, `phoneNumberNotUnique`, `ready`, `notConfigured`, `unknownFutureValue`.|



## Response

If successful, this method returns a `200 OK` response code and an updated [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_phoneauthenticationmethod"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/user/authentication/phoneMethods/{phoneAuthenticationMethodId}
Content-Type: application/json
Content-length: 152

{
  "@odata.type": "#microsoft.graph.phoneAuthenticationMethod",
  "phoneNumber": "String",
  "phoneType": "String",
  "smsSignInState": "String"
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
  "@odata.type": "#microsoft.graph.phoneAuthenticationMethod",
  "id": "7bc8825b-825b-7bc8-5b82-c87b5b82c87b",
  "phoneNumber": "String",
  "phoneType": "String",
  "smsSignInState": "String"
}
```

