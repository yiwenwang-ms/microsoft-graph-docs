---
title: "Update fido2AuthenticationMethod"
description: "Update the properties of a fido2AuthenticationMethod object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update fido2AuthenticationMethod
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) object.

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
PATCH /user/authentication/fido2Methods/{fido2AuthenticationMethodId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) object.

The following table shows the properties that are required when you update the [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [authenticationMethod](../resources/authenticationmethod.md)|
|displayName|String|**TODO: Add Description**|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|aaGuid|String|**TODO: Add Description**|
|model|String|**TODO: Add Description**|
|attestationCertificates|String collection|**TODO: Add Description**|
|attestationLevel|attestationLevel|**TODO: Add Description**. The possible values are: `attested`, `notAttested`, `unknownFutureValue`.|



## Response

If successful, this method returns a `200 OK` response code and an updated [fido2AuthenticationMethod](../resources/fido2authenticationmethod.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_fido2authenticationmethod"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/user/authentication/fido2Methods/{fido2AuthenticationMethodId}
Content-Type: application/json
Content-length: 270

{
  "@odata.type": "#microsoft.graph.fido2AuthenticationMethod",
  "displayName": "String",
  "creationDateTime": "String (timestamp)",
  "aaGuid": "String",
  "model": "String",
  "attestationCertificates": [
    "String"
  ],
  "attestationLevel": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.fido2AuthenticationMethod",
  "id": "3088b86d-b86d-3088-6db8-88306db88830",
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

