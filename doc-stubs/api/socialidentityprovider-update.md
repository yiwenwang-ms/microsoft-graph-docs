---
title: "Update socialIdentityProvider"
description: "Update the properties of a socialIdentityProvider object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update socialIdentityProvider
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [socialIdentityProvider](../resources/socialidentityprovider.md) object.

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
PATCH /socialIdentityProvider
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [socialIdentityProvider](../resources/socialidentityprovider.md) object.

The following table shows the properties that are required when you update the [socialIdentityProvider](../resources/socialidentityprovider.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md)|
|displayName|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md)|
|identityProviderType|String|**TODO: Add Description**|
|clientId|String|**TODO: Add Description**|
|clientSecret|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [socialIdentityProvider](../resources/socialidentityprovider.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_socialidentityprovider"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/socialIdentityProvider
Content-Type: application/json
Content-length: 183

{
  "@odata.type": "#microsoft.graph.socialIdentityProvider",
  "displayName": "String",
  "identityProviderType": "String",
  "clientId": "String",
  "clientSecret": "String"
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
  "@odata.type": "#microsoft.graph.socialIdentityProvider",
  "id": "11c02245-2245-11c0-4522-c0114522c011",
  "displayName": "String",
  "identityProviderType": "String",
  "clientId": "String",
  "clientSecret": "String"
}
```

