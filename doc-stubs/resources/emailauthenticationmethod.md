---
title: "emailAuthenticationMethod resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# emailAuthenticationMethod resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [authenticationMethod](../resources/authenticationmethod.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List emailAuthenticationMethods](../api/emailauthenticationmethod-list.md)|[emailAuthenticationMethod](../resources/emailauthenticationmethod.md) collection|Get a list of the [emailAuthenticationMethod](../resources/emailauthenticationmethod.md) objects and their properties.|
|[Create emailAuthenticationMethod](../api/emailauthenticationmethod-create.md)|[emailAuthenticationMethod](../resources/emailauthenticationmethod.md)|Create a new [emailAuthenticationMethod](../resources/emailauthenticationmethod.md) object.|
|[Get emailAuthenticationMethod](../api/emailauthenticationmethod-get.md)|[emailAuthenticationMethod](../resources/emailauthenticationmethod.md)|Read the properties and relationships of an [emailAuthenticationMethod](../resources/emailauthenticationmethod.md) object.|
|[Update emailAuthenticationMethod](../api/emailauthenticationmethod-update.md)|[emailAuthenticationMethod](../resources/emailauthenticationmethod.md)|Update the properties of an [emailAuthenticationMethod](../resources/emailauthenticationmethod.md) object.|
|[Delete emailAuthenticationMethod](../api/emailauthenticationmethod-delete.md)|None|Deletes an [emailAuthenticationMethod](../resources/emailauthenticationmethod.md) object.|
|[enableSmsSignIn](../api/emailauthenticationmethod-enablesmssignin.md)|None|**TODO: Add Description**|
|[disableSmsSignIn](../api/emailauthenticationmethod-disablesmssignin.md)|None|**TODO: Add Description**|
|[resetPassword](../api/emailauthenticationmethod-resetpassword.md)|[passwordResetResponse](../resources/passwordresetresponse.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|emailAddress|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [authenticationMethod](../resources/authenticationmethod.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.emailAuthenticationMethod",
  "baseType": "microsoft.strongAuthentication.authenticationMethod",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.emailAuthenticationMethod",
  "id": "String (identifier)",
  "emailAddress": "String"
}
```

