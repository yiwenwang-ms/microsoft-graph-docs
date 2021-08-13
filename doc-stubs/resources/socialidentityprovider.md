---
title: "socialIdentityProvider resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# socialIdentityProvider resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [identityProviderBase](../resources/identityproviderbase.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List socialIdentityProviders](../api/socialidentityprovider-list.md)|[socialIdentityProvider](../resources/socialidentityprovider.md) collection|Get a list of the [socialIdentityProvider](../resources/socialidentityprovider.md) objects and their properties.|
|[Create socialIdentityProvider](../api/socialidentityprovider-create.md)|[socialIdentityProvider](../resources/socialidentityprovider.md)|Create a new [socialIdentityProvider](../resources/socialidentityprovider.md) object.|
|[Get socialIdentityProvider](../api/socialidentityprovider-get.md)|[socialIdentityProvider](../resources/socialidentityprovider.md)|Read the properties and relationships of a [socialIdentityProvider](../resources/socialidentityprovider.md) object.|
|[Update socialIdentityProvider](../api/socialidentityprovider-update.md)|[socialIdentityProvider](../resources/socialidentityprovider.md)|Update the properties of a [socialIdentityProvider](../resources/socialidentityprovider.md) object.|
|[Delete socialIdentityProvider](../api/socialidentityprovider-delete.md)|None|Deletes a [socialIdentityProvider](../resources/socialidentityprovider.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|clientId|String|**TODO: Add Description**|
|clientSecret|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md).|
|id|String|**TODO: Add Description** Inherited from [identityProviderBase](../resources/identityproviderbase.md).|
|identityProviderType|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.socialIdentityProvider",
  "baseType": "Microsoft.Cpim.Api.DataModels.identityProviderBase",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.socialIdentityProvider",
  "id": "String (identifier)",
  "displayName": "String",
  "identityProviderType": "String",
  "clientId": "String",
  "clientSecret": "String"
}
```

