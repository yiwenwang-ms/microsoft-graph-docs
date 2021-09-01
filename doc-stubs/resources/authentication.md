---
title: "authentication resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# authentication resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List authentications](../api/authentication-list.md)|[authentication](../resources/authentication.md) collection|Get a list of the [authentication](../resources/authentication.md) objects and their properties.|
|[Create authentication](../api/authentication-create.md)|[authentication](../resources/authentication.md)|Create a new [authentication](../resources/authentication.md) object.|
|[Get authentication](../api/authentication-get.md)|[authentication](../resources/authentication.md)|Read the properties and relationships of an [authentication](../resources/authentication.md) object.|
|[Update authentication](../api/authentication-update.md)|[authentication](../resources/authentication.md)|Update the properties of an [authentication](../resources/authentication.md) object.|
|[Delete authentication](../api/authentication-delete.md)|None|Deletes an [authentication](../resources/authentication.md) object.|
|[List emailMethods](../api/authentication-list-emailmethods.md)|[emailAuthenticationMethod](../resources/emailauthenticationmethod.md) collection|Get the emailAuthenticationMethod resources from the emailMethods navigation property.|
|[Create emailAuthenticationMethod](../api/authentication-post-emailmethods.md)|[emailAuthenticationMethod](../resources/emailauthenticationmethod.md)|Create a new emailAuthenticationMethod object.|
|[List fido2Methods](../api/authentication-list-fido2methods.md)|[fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) collection|Get the fido2AuthenticationMethod resources from the fido2Methods navigation property.|
|[Create fido2AuthenticationMethod](../api/authentication-post-fido2methods.md)|[fido2AuthenticationMethod](../resources/fido2authenticationmethod.md)|Create a new fido2AuthenticationMethod object.|
|[List methods](../api/authentication-list-methods.md)|[authenticationMethod](../resources/authenticationmethod.md) collection|Get the authenticationMethod resources from the methods navigation property.|
|[Create authenticationMethod](../api/authentication-post-methods.md)|[authenticationMethod](../resources/authenticationmethod.md)|Create a new authenticationMethod object.|
|[List microsoftAuthenticatorMethods](../api/authentication-list-microsoftauthenticatormethods.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) collection|Get the microsoftAuthenticatorAuthenticationMethod resources from the microsoftAuthenticatorMethods navigation property.|
|[Create microsoftAuthenticatorAuthenticationMethod](../api/authentication-post-microsoftauthenticatormethods.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md)|Create a new microsoftAuthenticatorAuthenticationMethod object.|
|[List operations](../api/authentication-list-operations.md)|[longRunningOperation](../resources/longrunningoperation.md) collection|Get the longRunningOperation resources from the operations navigation property.|
|[Create longRunningOperation](../api/authentication-post-operations.md)|[longRunningOperation](../resources/longrunningoperation.md)|Create a new longRunningOperation object.|
|[List passwordlessMicrosoftAuthenticatorMethods](../api/authentication-list-passwordlessmicrosoftauthenticatormethods.md)|[passwordlessMicrosoftAuthenticatorAuthenticationMethod](../resources/passwordlessmicrosoftauthenticatorauthenticationmethod.md) collection|Get the passwordlessMicrosoftAuthenticatorAuthenticationMethod resources from the passwordlessMicrosoftAuthenticatorMethods navigation property.|
|[Create passwordlessMicrosoftAuthenticatorAuthenticationMethod](../api/authentication-post-passwordlessmicrosoftauthenticatormethods.md)|[passwordlessMicrosoftAuthenticatorAuthenticationMethod](../resources/passwordlessmicrosoftauthenticatorauthenticationmethod.md)|Create a new passwordlessMicrosoftAuthenticatorAuthenticationMethod object.|
|[List passwordMethods](../api/authentication-list-passwordmethods.md)|[passwordAuthenticationMethod](../resources/passwordauthenticationmethod.md) collection|Get the passwordAuthenticationMethod resources from the passwordMethods navigation property.|
|[Create passwordAuthenticationMethod](../api/authentication-post-passwordmethods.md)|[passwordAuthenticationMethod](../resources/passwordauthenticationmethod.md)|Create a new passwordAuthenticationMethod object.|
|[List phoneMethods](../api/authentication-list-phonemethods.md)|[phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) collection|Get the phoneAuthenticationMethod resources from the phoneMethods navigation property.|
|[Create phoneAuthenticationMethod](../api/authentication-post-phonemethods.md)|[phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md)|Create a new phoneAuthenticationMethod object.|
|[List softwareOathMethods](../api/authentication-list-softwareoathmethods.md)|[softwareOathAuthenticationMethod](../resources/softwareoathauthenticationmethod.md) collection|Get the softwareOathAuthenticationMethod resources from the softwareOathMethods navigation property.|
|[Create softwareOathAuthenticationMethod](../api/authentication-post-softwareoathmethods.md)|[softwareOathAuthenticationMethod](../resources/softwareoathauthenticationmethod.md)|Create a new softwareOathAuthenticationMethod object.|
|[List temporaryAccessPassMethods](../api/authentication-list-temporaryaccesspassmethods.md)|[temporaryAccessPassAuthenticationMethod](../resources/temporaryaccesspassauthenticationmethod.md) collection|Get the temporaryAccessPassAuthenticationMethod resources from the temporaryAccessPassMethods navigation property.|
|[Create temporaryAccessPassAuthenticationMethod](../api/authentication-post-temporaryaccesspassmethods.md)|[temporaryAccessPassAuthenticationMethod](../resources/temporaryaccesspassauthenticationmethod.md)|Create a new temporaryAccessPassAuthenticationMethod object.|
|[List windowsHelloForBusinessMethods](../api/authentication-list-windowshelloforbusinessmethods.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) collection|Get the windowsHelloForBusinessAuthenticationMethod resources from the windowsHelloForBusinessMethods navigation property.|
|[Create windowsHelloForBusinessAuthenticationMethod](../api/authentication-post-windowshelloforbusinessmethods.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md)|Create a new windowsHelloForBusinessAuthenticationMethod object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|policy|[authenticationMethodsPolicyEvaluation](../resources/authenticationmethodspolicyevaluation.md) collection|**TODO: Add Description**|
|strongAuthenticationStatus|strongAuthenticationStatus|**TODO: Add Description**. The possible values are: `none`, `perUserMfaEnabled`, `perUserMfaEnforced`, `unknownFutureValue`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|emailMethods|[emailAuthenticationMethod](../resources/emailauthenticationmethod.md) collection|**TODO: Add Description**|
|fido2Methods|[fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) collection|**TODO: Add Description**|
|methods|[authenticationMethod](../resources/authenticationmethod.md) collection|**TODO: Add Description**|
|microsoftAuthenticatorMethods|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) collection|**TODO: Add Description**|
|operations|[longRunningOperation](../resources/longrunningoperation.md) collection|**TODO: Add Description**|
|passwordlessMicrosoftAuthenticatorMethods|[passwordlessMicrosoftAuthenticatorAuthenticationMethod](../resources/passwordlessmicrosoftauthenticatorauthenticationmethod.md) collection|**TODO: Add Description**|
|passwordMethods|[passwordAuthenticationMethod](../resources/passwordauthenticationmethod.md) collection|**TODO: Add Description**|
|phoneMethods|[phoneAuthenticationMethod](../resources/phoneauthenticationmethod.md) collection|**TODO: Add Description**|
|securityQuestionMethods|[securityQuestionAuthenticationMethod](../resources/securityquestionauthenticationmethod.md) collection|**TODO: Add Description**|
|softwareOathMethods|[softwareOathAuthenticationMethod](../resources/softwareoathauthenticationmethod.md) collection|**TODO: Add Description**|
|temporaryAccessPassMethods|[temporaryAccessPassAuthenticationMethod](../resources/temporaryaccesspassauthenticationmethod.md) collection|**TODO: Add Description**|
|windowsHelloForBusinessMethods|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.authentication",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.authentication",
  "id": "String (identifier)",
  "policy": [
    {
      "@odata.type": "microsoft.graph.authenticationMethodsPolicyEvaluation"
    }
  ],
  "strongAuthenticationStatus": "String"
}
```

