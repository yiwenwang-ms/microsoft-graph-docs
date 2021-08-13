---
title: "Update openIdConnectProvider"
description: "Update the properties of an openIdConnectProvider object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update openIdConnectProvider
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [openIdConnectProvider](../resources/openidconnectprovider.md) object.

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
PATCH /openIdConnectProvider
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [openIdConnectProvider](../resources/openidconnectprovider.md) object.

The following table shows the properties that are required when you update the [openIdConnectProvider](../resources/openidconnectprovider.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md)|
|type|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md)|
|name|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md)|
|clientId|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md)|
|clientSecret|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md)|
|scope|String|**TODO: Add Description**|
|metadataUrl|String|**TODO: Add Description**|
|domainHint|String|**TODO: Add Description**|
|responseType|openIdConnectResponseTypes|**TODO: Add Description**. Possible values are: `code`, `id_token`, `token`.|
|responseMode|openIdConnectResponseMode|**TODO: Add Description**. Possible values are: `form_post`, `query`, `unknownFutureValue`.|
|claimsMapping|[Microsoft.Cpim.Api.DataModels.claimsMapping](../resources/claimsmapping.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [openIdConnectProvider](../resources/openidconnectprovider.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_openidconnectprovider"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/openIdConnectProvider
Content-Type: application/json
Content-length: 374

{
  "@odata.type": "#microsoft.graph.openIdConnectProvider",
  "type": "String",
  "name": "String",
  "clientId": "String",
  "clientSecret": "String",
  "scope": "String",
  "metadataUrl": "String",
  "domainHint": "String",
  "responseType": "String",
  "responseMode": "String",
  "claimsMapping": {
    "@odata.type": "microsoft.graph.claimsMapping"
  }
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
  "@odata.type": "#microsoft.graph.openIdConnectProvider",
  "id": "36033094-3094-3603-9430-033694300336",
  "type": "String",
  "name": "String",
  "clientId": "String",
  "clientSecret": "String",
  "scope": "String",
  "metadataUrl": "String",
  "domainHint": "String",
  "responseType": "String",
  "responseMode": "String",
  "claimsMapping": {
    "@odata.type": "microsoft.graph.claimsMapping"
  }
}
```

