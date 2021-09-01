---
title: "fido2AuthenticationMethod resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# fido2AuthenticationMethod resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [authenticationMethod](../resources/authenticationmethod.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List fido2AuthenticationMethod](../api/fido2authenticationmethod-list.md)|[fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) collection|Get a list of the [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) objects and their properties.|
|[Create fido2AuthenticationMethod](../api/fido2authenticationmethod-create.md)|[fido2AuthenticationMethod](../resources/fido2authenticationmethod.md)|Create a new [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) object.|
|[Get fido2AuthenticationMethod](../api/fido2authenticationmethod-get.md)|[fido2AuthenticationMethod](../resources/fido2authenticationmethod.md)|Read the properties and relationships of a [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) object.|
|[Update fido2AuthenticationMethod](../api/fido2authenticationmethod-update.md)|[fido2AuthenticationMethod](../resources/fido2authenticationmethod.md)|Update the properties of a [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) object.|
|[Delete fido2AuthenticationMethod](../api/fido2authenticationmethod-delete.md)|None|Deletes a [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) object.|
|[enableSmsSignIn](../api/fido2authenticationmethod-enablesmssignin.md)|None|**TODO: Add Description**|
|[disableSmsSignIn](../api/fido2authenticationmethod-disablesmssignin.md)|None|**TODO: Add Description**|
|[resetPassword](../api/fido2authenticationmethod-resetpassword.md)|[passwordResetResponse](../resources/passwordresetresponse.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|aaGuid|String|**TODO: Add Description**|
|attestationCertificates|String collection|**TODO: Add Description**|
|attestationLevel|attestationLevel|**TODO: Add Description**. The possible values are: `attested`, `notAttested`, `unknownFutureValue`.|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [authenticationMethod](../resources/authenticationmethod.md).|
|model|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.fido2AuthenticationMethod",
  "baseType": "microsoft.strongAuthentication.authenticationMethod",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.fido2AuthenticationMethod",
  "id": "String (identifier)",
  "displayName": "String",
  "creationDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "aaGuid": "String",
  "model": "String",
  "attestationCertificates": [
    "String"
  ],
  "attestationLevel": "String"
}
```

