---
title: "builtInIdentityProvider resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# builtInIdentityProvider resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [identityProviderBase](../resources/identityproviderbase.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List builtInIdentityProviders](../api/builtinidentityprovider-list.md)|[builtInIdentityProvider](../resources/builtinidentityprovider.md) collection|Get a list of the [builtInIdentityProvider](../resources/builtinidentityprovider.md) objects and their properties.|
|[Create builtInIdentityProvider](../api/builtinidentityprovider-create.md)|[builtInIdentityProvider](../resources/builtinidentityprovider.md)|Create a new [builtInIdentityProvider](../resources/builtinidentityprovider.md) object.|
|[Get builtInIdentityProvider](../api/builtinidentityprovider-get.md)|[builtInIdentityProvider](../resources/builtinidentityprovider.md)|Read the properties and relationships of a [builtInIdentityProvider](../resources/builtinidentityprovider.md) object.|
|[Update builtInIdentityProvider](../api/builtinidentityprovider-update.md)|[builtInIdentityProvider](../resources/builtinidentityprovider.md)|Update the properties of a [builtInIdentityProvider](../resources/builtinidentityprovider.md) object.|
|[Delete builtInIdentityProvider](../api/builtinidentityprovider-delete.md)|None|Deletes a [builtInIdentityProvider](../resources/builtinidentityprovider.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
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
  "@odata.type": "microsoft.graph.builtInIdentityProvider",
  "baseType": "Microsoft.Cpim.Api.DataModels.identityProviderBase",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.builtInIdentityProvider",
  "id": "String (identifier)",
  "displayName": "String",
  "identityProviderType": "String"
}
```

