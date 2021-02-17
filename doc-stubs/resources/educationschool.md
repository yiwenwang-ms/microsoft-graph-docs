---
title: "educationSchool resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationSchool resource type

Namespace: microsoft.graph



**TODO: Add Description**


Inherits from [educationOrganization](../resources/educationorganization.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationSchools](../api/educationschool-list.md)|[educationSchool](../resources/educationschool.md) collection|Get a list of the [educationSchool](../resources/educationschool.md) objects and their properties.|
|[Create educationSchool](../api/educationschool-create.md)|[educationSchool](../resources/educationschool.md)|Create a new [educationSchool](../resources/educationschool.md) object.|
|[Get educationSchool](../api/educationschool-get.md)|[educationSchool](../resources/educationschool.md)|Read the properties and relationships of an [educationSchool](../resources/educationschool.md) object.|
|[Update educationSchool](../api/educationschool-update.md)|[educationSchool](../resources/educationschool.md)|Update the properties of an [educationSchool](../resources/educationschool.md) object.|
|[Delete educationSchool](../api/educationschool-delete.md)|None|Deletes an [educationSchool](../resources/educationschool.md) object.|
|[delta](../api/educationschool-delta.md)|[educationSchool](../resources/educationschool.md) collection|**TODO: Add Description**|
|[List administrativeUnit](../api/educationschool-list-administrativeunit.md)|[administrativeUnit](../resources/administrativeunit.md) collection|Get the administrativeUnit resources from the administrativeUnit navigation property.|
|[Add administrativeUnit](../api/educationschool-post-administrativeunit.md)|[administrativeUnit](../resources/administrativeunit.md)|Add administrativeUnit by posting to the administrativeUnit collection.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|address|[physicalAddress](../resources/physicaladdress.md)|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|description|String|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md)|
|displayName|String|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md)|
|externalId|String|**TODO: Add Description**|
|externalPrincipalId|String|**TODO: Add Description**|
|externalSource|educationExternalSource|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md). Possible values are: `sis`, `manual`, `unknownFutureValue`.|
|externalSourceDetail|String|**TODO: Add Description** Inherited from [educationOrganization](../resources/educationorganization.md)|
|fax|String|**TODO: Add Description**|
|highestGrade|String|**TODO: Add Description**|
|lowestGrade|String|**TODO: Add Description**|
|phone|String|**TODO: Add Description**|
|principalEmail|String|**TODO: Add Description**|
|principalName|String|**TODO: Add Description**|
|schoolNumber|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|administrativeUnit|[administrativeUnit](../resources/administrativeunit.md)|**TODO: Add Description**|
|classes|[educationClass](../resources/educationclass.md) collection|**TODO: Add Description**|
|users|[educationUser](../resources/educationuser.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.educationSchool",
  "baseType": "microsoft.education.rostering.api.educationOrganization",
  "openType": false
}
-->
``` json
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

