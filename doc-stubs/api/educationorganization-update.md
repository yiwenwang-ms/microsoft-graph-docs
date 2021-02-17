---
title: "Update educationOrganization"
description: "Update the properties of an educationOrganization object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update educationOrganization
Namespace: microsoft.graph



Update the properties of an [educationOrganization](../resources/educationorganization.md) object.

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
PATCH /educationOrganization
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [educationOrganization](../resources/educationorganization.md) object.

The following table shows the properties that are required when you update the [educationOrganization](../resources/educationorganization.md).

|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|externalSource|educationExternalSource|**TODO: Add Description**. Possible values are: `sis`, `manual`, `unknownFutureValue`.|
|externalSourceDetail|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [educationOrganization](../resources/educationorganization.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_educationorganization"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/educationOrganization
Content-Type: application/json
Content-length: 187

{
  "@odata.type": "#microsoft.graph.educationOrganization",
  "displayName": "String",
  "description": "String",
  "externalSource": "String",
  "externalSourceDetail": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.educationOrganization",
  "displayName": "String",
  "description": "String",
  "externalSource": "String",
  "externalSourceDetail": "String"
}
```

