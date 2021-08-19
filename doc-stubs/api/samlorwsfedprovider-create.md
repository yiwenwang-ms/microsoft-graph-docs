---
title: "Create samlOrWsFedProvider"
description: "Create a new samlOrWsFedProvider object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create samlOrWsFedProvider
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [samlOrWsFedProvider](../resources/samlorwsfedprovider.md) object.

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
POST ** Collection URI for microsoft.graph.samlOrWsFedProvider not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [samlOrWsFedProvider](../resources/samlorwsfedprovider.md) object.

The following table shows the properties that are required when you create the [samlOrWsFedProvider](../resources/samlorwsfedprovider.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md)|
|issuerUri|String|**TODO: Add Description**|
|metadataExchangeUri|String|**TODO: Add Description**|
|signingCertificate|String|**TODO: Add Description**|
|passiveSignInUri|String|**TODO: Add Description**|
|preferredAuthenticationProtocol|String|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [samlOrWsFedProvider](../resources/samlorwsfedprovider.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_samlorwsfedprovider_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.samlOrWsFedProvider not found
Content-Type: application/json
Content-length: 267

{
  "@odata.type": "#microsoft.graph.samlOrWsFedProvider",
  "displayName": "String",
  "issuerUri": "String",
  "metadataExchangeUri": "String",
  "signingCertificate": "String",
  "passiveSignInUri": "String",
  "preferredAuthenticationProtocol": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.samlOrWsFedProvider"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.samlOrWsFedProvider",
  "id": "d9f29833-9833-d9f2-3398-f2d93398f2d9",
  "displayName": "String",
  "issuerUri": "String",
  "metadataExchangeUri": "String",
  "signingCertificate": "String",
  "passiveSignInUri": "String",
  "preferredAuthenticationProtocol": "String"
}
```

