---
title: "phoneAuthenticationMethod resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# phoneAuthenticationMethod resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [authenticationMethod](../resources/authenticationmethod.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List phoneAuthenticationMethods](../api/phoneauthenticationmethod-list.md)|[phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) collection|Get a list of the [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) objects and their properties.|
|[Create phoneAuthenticationMethod](../api/phoneauthenticationmethod-create.md)|[phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md)|Create a new [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) object.|
|[Get phoneAuthenticationMethod](../api/phoneauthenticationmethod-get.md)|[phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md)|Read the properties and relationships of a [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) object.|
|[Update phoneAuthenticationMethod](../api/phoneauthenticationmethod-update.md)|[phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md)|Update the properties of a [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) object.|
|[Delete phoneAuthenticationMethod](../api/phoneauthenticationmethod-delete.md)|None|Deletes a [phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) object.|
|[enableSmsSignIn](../api/phoneauthenticationmethod-enablesmssignin.md)|None|**TODO: Add Description**|
|[disableSmsSignIn](../api/phoneauthenticationmethod-disablesmssignin.md)|None|**TODO: Add Description**|
|[resetPassword](../api/phoneauthenticationmethod-resetpassword.md)|[passwordResetResponse](../resources/passwordresetresponse.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [authenticationMethod](../resources/authenticationmethod.md).|
|phoneNumber|String|**TODO: Add Description**|
|phoneType|authenticationPhoneType|**TODO: Add Description**. The possible values are: `mobile`, `alternateMobile`, `office`, `unknownFutureValue`.|
|smsSignInState|authenticationMethodSignInState|**TODO: Add Description**. The possible values are: `notSupported`, `notAllowedByPolicy`, `notEnabled`, `phoneNumberNotUnique`, `ready`, `notConfigured`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.phoneAuthenticationMethod",
  "baseType": "microsoft.strongAuthentication.authenticationMethod",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.phoneAuthenticationMethod",
  "id": "String (identifier)",
  "phoneNumber": "String",
  "phoneType": "String",
  "smsSignInState": "String"
}
```

