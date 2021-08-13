---
title: "openIdConnectIdentityProvider resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# openIdConnectIdentityProvider resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [identityProviderBase](../resources/identityproviderbase.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List openIdConnectIdentityProviders](../api/openidconnectidentityprovider-list.md)|[openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md) collection|Get a list of the [openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md) objects and their properties.|
|[Create openIdConnectIdentityProvider](../api/openidconnectidentityprovider-create.md)|[openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md)|Create a new [openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md) object.|
|[Get openIdConnectIdentityProvider](../api/openidconnectidentityprovider-get.md)|[openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md)|Read the properties and relationships of an [openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md) object.|
|[Update openIdConnectIdentityProvider](../api/openidconnectidentityprovider-update.md)|[openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md)|Update the properties of an [openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md) object.|
|[Delete openIdConnectIdentityProvider](../api/openidconnectidentityprovider-delete.md)|None|Deletes an [openIdConnectIdentityProvider](../resources/openidconnectidentityprovider.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|claimsMapping|[claimsMapping](../resources/claimsmapping.md)|**TODO: Add Description**|
|clientId|String|**TODO: Add Description**|
|clientSecret|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md).|
|domainHint|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md).|
|metadataUrl|String|**TODO: Add Description**|
|responseMode|openIdConnectResponseMode|**TODO: Add Description**. Possible values are: `form_post`, `query`, `unknownFutureValue`.|
|responseType|openIdConnectResponseTypes|**TODO: Add Description**. Possible values are: `code`, `id_token`, `token`.|
|scope|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.openIdConnectIdentityProvider",
  "baseType": "Microsoft.Cpim.Api.DataModels.identityProviderBase",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.openIdConnectIdentityProvider",
  "id": "String (identifier)",
  "displayName": "String",
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

