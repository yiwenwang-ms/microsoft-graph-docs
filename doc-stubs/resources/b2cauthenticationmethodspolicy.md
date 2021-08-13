---
title: "b2cAuthenticationMethodsPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# b2cAuthenticationMethodsPolicy resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List b2cAuthenticationMethodsPolicy](../api/b2cauthenticationmethodspolicy-list.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) collection|Get a list of the [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) objects and their properties.|
|[Create b2cAuthenticationMethodsPolicy](../api/b2cauthenticationmethodspolicy-create.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md)|Create a new [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object.|
|[Get b2cAuthenticationMethodsPolicy](../api/b2cauthenticationmethodspolicy-get.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md)|Read the properties and relationships of a [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object.|
|[Update b2cAuthenticationMethodsPolicy](../api/b2cauthenticationmethodspolicy-update.md)|[b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md)|Update the properties of a [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object.|
|[Delete b2cAuthenticationMethodsPolicy](../api/b2cauthenticationmethodspolicy-delete.md)|None|Deletes a [b2cAuthenticationMethodsPolicy](../resources/b2cauthenticationmethodspolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|isEmailPasswordAuthenticationEnabled|Boolean|**TODO: Add Description**|
|isPhoneOneTimePasswordAuthenticationEnabled|Boolean|**TODO: Add Description**|
|isUserNameAuthenticationEnabled|Boolean|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.b2cAuthenticationMethodsPolicy",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.b2cAuthenticationMethodsPolicy",
  "isPhoneOneTimePasswordAuthenticationEnabled": "Boolean",
  "isEmailPasswordAuthenticationEnabled": "Boolean",
  "isUserNameAuthenticationEnabled": "Boolean"
}
```

