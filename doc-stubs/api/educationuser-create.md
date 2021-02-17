---
title: "Create educationUser"
description: "Create a new educationUser object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create educationUser
Namespace: microsoft.graph



Create a new [educationUser](../resources/educationuser.md) object.

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
POST /education/users
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [educationUser](../resources/educationuser.md) object.

The following table shows the properties that are required when you create the [educationUser](../resources/educationuser.md).

|Property|Type|Description|
|:---|:---|:---|
|primaryRole|educationUserRole|**TODO: Add Description**. Possible values are: `student`, `teacher`, `none`, `unknownFutureValue`.|
|middleName|String|**TODO: Add Description**|
|externalSource|educationExternalSource|**TODO: Add Description**. Possible values are: `sis`, `manual`, `unknownFutureValue`.|
|externalSourceDetail|String|**TODO: Add Description**|
|residenceAddress|[physicalAddress](../resources/physicaladdress.md)|**TODO: Add Description**|
|mailingAddress|[physicalAddress](../resources/physicaladdress.md)|**TODO: Add Description**|
|student|[educationStudent](../resources/educationstudent.md)|**TODO: Add Description**|
|teacher|[educationTeacher](../resources/educationteacher.md)|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|accountEnabled|Boolean|**TODO: Add Description**|
|assignedLicenses|[assignedLicense](../resources/assignedlicense.md) collection|**TODO: Add Description**|
|assignedPlans|[assignedPlan](../resources/assignedplan.md) collection|**TODO: Add Description**|
|businessPhones|String collection|**TODO: Add Description**|
|department|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|givenName|String|**TODO: Add Description**|
|mail|String|**TODO: Add Description**|
|mailNickname|String|**TODO: Add Description**|
|mobilePhone|String|**TODO: Add Description**|
|passwordPolicies|String|**TODO: Add Description**|
|passwordProfile|[passwordProfile](../resources/passwordprofile.md)|**TODO: Add Description**|
|officeLocation|String|**TODO: Add Description**|
|preferredLanguage|String|**TODO: Add Description**|
|provisionedPlans|[provisionedPlan](../resources/provisionedplan.md) collection|**TODO: Add Description**|
|refreshTokensValidFromDateTime|DateTimeOffset|**TODO: Add Description**|
|showInAddressList|Boolean|**TODO: Add Description**|
|surname|String|**TODO: Add Description**|
|usageLocation|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|
|userType|String|**TODO: Add Description**|
|onPremisesInfo|[educationOnPremisesInfo](../resources/educationonpremisesinfo.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and an [educationUser](../resources/educationuser.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_educationuser_from_"
}
-->
``` http
POST https://graph.microsoft.com/v1.0/education/users
Content-Type: application/json
Content-length: 1603

{
  "@odata.type": "#microsoft.education.rostering.api.educationUser",
  "primaryRole": "String",
  "middleName": "String",
  "externalSource": "String",
  "externalSourceDetail": "String",
  "residenceAddress": {
    "@odata.type": "microsoft.graph.physicalAddress"
  },
  "mailingAddress": {
    "@odata.type": "microsoft.graph.physicalAddress"
  },
  "student": {
    "@odata.type": "microsoft.graph.educationStudent"
  },
  "teacher": {
    "@odata.type": "microsoft.graph.educationTeacher"
  },
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "accountEnabled": "Boolean",
  "assignedLicenses": [
    {
      "@odata.type": "microsoft.graph.assignedLicense"
    }
  ],
  "assignedPlans": [
    {
      "@odata.type": "microsoft.graph.assignedPlan"
    }
  ],
  "businessPhones": [
    "String"
  ],
  "department": "String",
  "displayName": "String",
  "givenName": "String",
  "mail": "String",
  "mailNickname": "String",
  "mobilePhone": "String",
  "passwordPolicies": "String",
  "passwordProfile": {
    "@odata.type": "microsoft.graph.passwordProfile"
  },
  "officeLocation": "String",
  "preferredLanguage": "String",
  "provisionedPlans": [
    {
      "@odata.type": "microsoft.graph.provisionedPlan"
    }
  ],
  "refreshTokensValidFromDateTime": "String (timestamp)",
  "showInAddressList": "Boolean",
  "surname": "String",
  "usageLocation": "String",
  "userPrincipalName": "String",
  "userType": "String",
  "onPremisesInfo": {
    "@odata.type": "microsoft.graph.educationOnPremisesInfo"
  }
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.education.rostering.api.educationUser"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.education.rostering.api.educationUser",
  "primaryRole": "String",
  "middleName": "String",
  "externalSource": "String",
  "externalSourceDetail": "String",
  "residenceAddress": {
    "@odata.type": "microsoft.graph.physicalAddress"
  },
  "mailingAddress": {
    "@odata.type": "microsoft.graph.physicalAddress"
  },
  "student": {
    "@odata.type": "microsoft.graph.educationStudent"
  },
  "teacher": {
    "@odata.type": "microsoft.graph.educationTeacher"
  },
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "accountEnabled": "Boolean",
  "assignedLicenses": [
    {
      "@odata.type": "microsoft.graph.assignedLicense"
    }
  ],
  "assignedPlans": [
    {
      "@odata.type": "microsoft.graph.assignedPlan"
    }
  ],
  "businessPhones": [
    "String"
  ],
  "department": "String",
  "displayName": "String",
  "givenName": "String",
  "mail": "String",
  "mailNickname": "String",
  "mobilePhone": "String",
  "passwordPolicies": "String",
  "passwordProfile": {
    "@odata.type": "microsoft.graph.passwordProfile"
  },
  "officeLocation": "String",
  "preferredLanguage": "String",
  "provisionedPlans": [
    {
      "@odata.type": "microsoft.graph.provisionedPlan"
    }
  ],
  "refreshTokensValidFromDateTime": "String (timestamp)",
  "showInAddressList": "Boolean",
  "surname": "String",
  "usageLocation": "String",
  "userPrincipalName": "String",
  "userType": "String",
  "onPremisesInfo": {
    "@odata.type": "microsoft.graph.educationOnPremisesInfo"
  }
}
```

