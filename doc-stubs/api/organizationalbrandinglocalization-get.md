---
title: "Get organizationalBrandingLocalization"
description: "Read the properties and relationships of an organizationalBrandingLocalization object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get organizationalBrandingLocalization
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of an [organizationalBrandingLocalization](../resources/organizationalbrandinglocalization.md) object.

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
GET /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and an [organizationalBrandingLocalization](../resources/organizationalbrandinglocalization.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_organizationalbrandinglocalization"
}
-->
``` http
GET https://graph.microsoft.com/beta/organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.DirectoryServices.organizationalBrandingLocalization"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#Microsoft.DirectoryServices.organizationalBrandingLocalization",
    "id": "e91971b3-71b3-e919-b371-19e9b37119e9",
    "backgroundColor": "String",
    "backgroundImage": "Stream",
    "backgroundImageRelativeUrl": "String",
    "bannerLogo": "Stream",
    "bannerLogoRelativeUrl": "String",
    "cdnList": [
      "String"
    ],
    "signInPageText": "String",
    "squareLogo": "Stream",
    "squareLogoRelativeUrl": "String",
    "usernameHintText": "String",
    "customAccountResetCredentialsUrl": "String",
    "customCannotAccessYourAccountText": "String",
    "customCannotAccessYourAccountUrl": "String",
    "customForgotMyPasswordText": "String",
    "customPrivacyAndCookiesText": "String",
    "customPrivacyAndCookiesUrl": "String",
    "customResetItNowText": "String",
    "customTermsOfUseText": "String",
    "customTermsOfUseUrl": "String",
    "favicon": "Stream",
    "faviconRelativeUrl": "String",
    "headerBackgroundColor": "String",
    "loginPageTextVisibilitySettings": {
      "@odata.type": "microsoft.graph.loginPageTextVisibilitySettings"
    }
  }
}
```

