---
title: "Create authentication"
description: "Create a new authentication object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create authentication
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new authentication object.

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
POST /user/authentication
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [authentication](../resources/authentication.md) object.

The following table shows the properties that are required when you create the [authentication](../resources/authentication.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|policy|[microsoft.strongAuthentication.authenticationMethodsPolicyEvaluation](../resources/authenticationmethodspolicyevaluation.md) collection|**TODO: Add Description**|
|strongAuthenticationStatus|strongAuthenticationStatus|**TODO: Add Description**. The possible values are: `none`, `perUserMfaEnabled`, `perUserMfaEnforced`, `unknownFutureValue`.|



## Response

If successful, this method returns a `201 Created` response code and an [authentication](../resources/authentication.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_authentication_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/user/authentication
Content-Type: application/json
Content-length: 227

{
  "@odata.type": "#microsoft.strongAuthentication.authentication",
  "policy": [
    {
      "@odata.type": "microsoft.graph.authenticationMethodsPolicyEvaluation"
    }
  ],
  "strongAuthenticationStatus": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.strongAuthentication.authentication"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.strongAuthentication.authentication",
  "id": "5662f6c4-f6c4-5662-c4f6-6256c4f66256",
  "policy": [
    {
      "@odata.type": "microsoft.graph.authenticationMethodsPolicyEvaluation"
    }
  ],
  "strongAuthenticationStatus": "String"
}
```

