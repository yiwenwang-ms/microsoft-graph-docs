---
title: "Update educationClass"
description: "Update the properties of an educationClass object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update educationClass
Namespace: microsoft.graph



Update the properties of an [educationClass](../resources/educationclass.md) object.

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
PATCH /education/classes/{educationClassId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [educationClass](../resources/educationclass.md) object.

The following table shows the properties that are required when you update the [educationClass](../resources/educationclass.md).

|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|mailNickname|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|classCode|String|**TODO: Add Description**|
|externalName|String|**TODO: Add Description**|
|externalId|String|**TODO: Add Description**|
|externalSource|educationExternalSource|**TODO: Add Description**. Possible values are: `sis`, `manual`, `unknownFutureValue`.|
|externalSourceDetail|String|**TODO: Add Description**|
|grade|String|**TODO: Add Description**|
|term|[educationTerm](../resources/educationterm.md)|**TODO: Add Description**|
|course|[educationCourse](../resources/educationcourse.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [educationClass](../resources/educationclass.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_educationclass"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/education/classes/{educationClassId}
Content-Type: application/json
Content-length: 533

{
  "@odata.type": "#microsoft.graph.educationClass",
  "displayName": "String",
  "mailNickname": "String",
  "description": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "classCode": "String",
  "externalName": "String",
  "externalId": "String",
  "externalSource": "String",
  "externalSourceDetail": "String",
  "grade": "String",
  "term": {
    "@odata.type": "microsoft.graph.educationTerm"
  },
  "course": {
    "@odata.type": "microsoft.graph.educationCourse"
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
  "@odata.type": "#microsoft.graph.educationClass",
  "displayName": "String",
  "mailNickname": "String",
  "description": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "classCode": "String",
  "externalName": "String",
  "externalId": "String",
  "externalSource": "String",
  "externalSourceDetail": "String",
  "grade": "String",
  "term": {
    "@odata.type": "microsoft.graph.educationTerm"
  },
  "course": {
    "@odata.type": "microsoft.graph.educationCourse"
  }
}
```

