---
title: "openIdConnectProvider resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# openIdConnectProvider resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [identityProvider](../resources/identityprovider.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List openIdConnectProviders](../api/openidconnectprovider-list.md)|[openIdConnectProvider](../resources/openidconnectprovider.md) collection|Get a list of the [openIdConnectProvider](../resources/openidconnectprovider.md) objects and their properties.|
|[Create openIdConnectProvider](../api/openidconnectprovider-create.md)|[openIdConnectProvider](../resources/openidconnectprovider.md)|Create a new [openIdConnectProvider](../resources/openidconnectprovider.md) object.|
|[Get openIdConnectProvider](../api/openidconnectprovider-get.md)|[openIdConnectProvider](../resources/openidconnectprovider.md)|Read the properties and relationships of an [openIdConnectProvider](../resources/openidconnectprovider.md) object.|
|[Update openIdConnectProvider](../api/openidconnectprovider-update.md)|[openIdConnectProvider](../resources/openidconnectprovider.md)|Update the properties of an [openIdConnectProvider](../resources/openidconnectprovider.md) object.|
|[Delete openIdConnectProvider](../api/openidconnectprovider-delete.md)|None|Deletes an [openIdConnectProvider](../resources/openidconnectprovider.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|claimsMapping|[claimsMapping](../resources/claimsmapping.md)|**TODO: Add Description**|
|clientId|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md).|
|clientSecret|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md).|
|domainHint|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md).|
|metadataUrl|String|**TODO: Add Description**|
|name|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md).|
|responseMode|openIdConnectResponseMode|**TODO: Add Description**. Possible values are: `form_post`, `query`, `unknownFutureValue`.|
|responseType|openIdConnectResponseTypes|**TODO: Add Description**. Possible values are: `code`, `id_token`, `token`.|
|scope|String|**TODO: Add Description**|
|type|String|**TODO: Add Description** Inherited from [identityProvider](../resources/identityprovider.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.openIdConnectProvider",
  "baseType": "Microsoft.Cpim.Api.DataModels.identityProvider",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.openIdConnectProvider",
  "id": "String (identifier)",
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

