---
title: "Update educationSchool"
description: "Update the properties of an educationSchool object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update educationSchool
Namespace: microsoft.graph



Update the properties of an [educationSchool](../resources/educationschool.md) object.

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
PATCH /education/schools/{educationSchoolId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [educationSchool](../resources/educationschool.md) object.

The following table shows the properties that are required when you update the [educationSchool](../resources/educationschool.md).

|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md)|
|description|String|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md)|
|externalSource|educationExternalSource|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md). Possible values are: `sis`, `manual`, `unknownFutureValue`.|
|externalSourceDetail|String|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md)|
|principalEmail|String|**TODO: Add Description**|
|principalName|String|**TODO: Add Description**|
|externalPrincipalId|String|**TODO: Add Description**|
|lowestGrade|String|**TODO: Add Description**|
|highestGrade|String|**TODO: Add Description**|
|schoolNumber|String|**TODO: Add Description**|
|externalId|String|**TODO: Add Description**|
|phone|String|**TODO: Add Description**|
|fax|String|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|address|[physicalAddress](../resources/physicaladdress.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [educationSchool](../resources/educationschool.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_educationschool"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/education/schools/{educationSchoolId}
Content-Type: application/json
Content-length: 583

{
  "@odata.type": "#microsoft.graph.educationSchool",
  "displayName": "String",
  "description": "String",
  "externalSource": "String",
  "externalSourceDetail": "String",
  "principalEmail": "String",
  "principalName": "String",
  "externalPrincipalId": "String",
  "lowestGrade": "String",
  "highestGrade": "String",
  "schoolNumber": "String",
  "externalId": "String",
  "phone": "String",
  "fax": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "address": {
    "@odata.type": "microsoft.graph.physicalAddress"
  }
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
  "@odata.type": "#microsoft.graph.educationSchool",
  "displayName": "String",
  "description": "String",
  "externalSource": "String",
  "externalSourceDetail": "String",
  "principalEmail": "String",
  "principalName": "String",
  "externalPrincipalId": "String",
  "lowestGrade": "String",
  "highestGrade": "String",
  "schoolNumber": "String",
  "externalId": "String",
  "phone": "String",
  "fax": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "address": {
    "@odata.type": "microsoft.graph.physicalAddress"
  }
}
```

