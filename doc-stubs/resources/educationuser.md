---
title: "educationUser resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationUser resource type

Namespace: microsoft.graph



**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationUsers](../api/educationuser-list.md)|[educationUser](../resources/educationuser.md) collection|Get a list of the [educationUser](../resources/educationuser.md) objects and their properties.|
|[Create educationUser](../api/educationuser-create.md)|[educationUser](../resources/educationuser.md)|Create a new [educationUser](../resources/educationuser.md) object.|
|[Get educationUser](../api/educationuser-get.md)|[educationUser](../resources/educationuser.md)|Read the properties and relationships of an [educationUser](../resources/educationuser.md) object.|
|[Update educationUser](../api/educationuser-update.md)|[educationUser](../resources/educationuser.md)|Update the properties of an [educationUser](../resources/educationuser.md) object.|
|[Delete educationUser](../api/educationuser-delete.md)|None|Deletes an [educationUser](../resources/educationuser.md) object.|
|[delta](../api/educationuser-delta.md)|[educationUser](../resources/educationuser.md) collection|**TODO: Add Description**|
|[List taughtClasses](../api/educationuser-list-taughtclasses.md)|[educationClass](../resources/educationclass.md) collection|Get the educationClass resources from the taughtClasses navigation property.|
|[Add educationClass](../api/educationuser-post-taughtclasses.md)|[educationClass](../resources/educationclass.md)|Add taughtClasses by posting to the taughtClasses collection.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|accountEnabled|Boolean|**TODO: Add Description**|
|assignedLicenses|[assignedLicense](../resources/assignedlicense.md) collection|**TODO: Add Description**|
|assignedPlans|[assignedPlan](../resources/assignedplan.md) collection|**TODO: Add Description**|
|businessPhones|String collection|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|department|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|externalSource|educationExternalSource|**TODO: Add Description**. Possible values are: `sis`, `manual`, `unknownFutureValue`.|
|externalSourceDetail|String|**TODO: Add Description**|
|givenName|String|**TODO: Add Description**|
|mail|String|**TODO: Add Description**|
|mailingAddress|[physicalAddress](../resources/physicaladdress.md)|**TODO: Add Description**|
|mailNickname|String|**TODO: Add Description**|
|middleName|String|**TODO: Add Description**|
|mobilePhone|String|**TODO: Add Description**|
|officeLocation|String|**TODO: Add Description**|
|onPremisesInfo|[educationOnPremisesInfo](../resources/educationonpremisesinfo.md)|**TODO: Add Description**|
|passwordPolicies|String|**TODO: Add Description**|
|passwordProfile|[passwordProfile](../resources/passwordprofile.md)|**TODO: Add Description**|
|preferredLanguage|String|**TODO: Add Description**|
|primaryRole|educationUserRole|**TODO: Add Description**. Possible values are: `student`, `teacher`, `none`, `unknownFutureValue`.|
|provisionedPlans|[provisionedPlan](../resources/provisionedplan.md) collection|**TODO: Add Description**|
|refreshTokensValidFromDateTime|DateTimeOffset|**TODO: Add Description**|
|residenceAddress|[physicalAddress](../resources/physicaladdress.md)|**TODO: Add Description**|
|showInAddressList|Boolean|**TODO: Add Description**|
|student|[educationStudent](../resources/educationstudent.md)|**TODO: Add Description**|
|surname|String|**TODO: Add Description**|
|teacher|[educationTeacher](../resources/educationteacher.md)|**TODO: Add Description**|
|usageLocation|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|
|userType|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|classes|[educationClass](../resources/educationclass.md) collection|**TODO: Add Description**|
|schools|[educationSchool](../resources/educationschool.md) collection|**TODO: Add Description**|
|taughtClasses|[educationClass](../resources/educationclass.md) collection|**TODO: Add Description**|
|user|[user](../resources/user.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.educationUser",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationUser",
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

