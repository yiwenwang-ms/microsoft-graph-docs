---
title: "Create socialIdentityProvider"
description: "Create a new socialIdentityProvider object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create socialIdentityProvider
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [socialIdentityProvider](../resources/socialidentityprovider.md) object.

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
POST ** Collection URI for Microsoft.Cpim.Api.DataModels.socialIdentityProvider not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [socialIdentityProvider](../resources/socialidentityprovider.md) object.

The following table shows the properties that are required when you create the [socialIdentityProvider](../resources/socialidentityprovider.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md)|
|displayName|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md)|
|identityProviderType|String|**TODO: Add Description**|
|clientId|String|**TODO: Add Description**|
|clientSecret|String|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [socialIdentityProvider](../resources/socialidentityprovider.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_socialidentityprovider_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for Microsoft.Cpim.Api.DataModels.socialIdentityProvider not found
Content-Type: application/json
Content-length: 197

{
  "@odata.type": "#Microsoft.Cpim.Api.DataModels.socialIdentityProvider",
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
  "truncated": true,
  "@odata.type": "Microsoft.Cpim.Api.DataModels.socialIdentityProvider"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.Cpim.Api.DataModels.socialIdentityProvider",
  "id": "11c02245-2245-11c0-4522-c0114522c011",
  "displayName": "String",
  "identityProviderType": "String",
  "clientId": "String",
  "clientSecret": "String"
}
```

