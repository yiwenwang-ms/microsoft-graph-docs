---
title: "educationOrganization resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationOrganization resource type

Namespace: microsoft.graph



**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationOrganizations](../api/educationorganization-list.md)|[educationOrganization](../resources/educationorganization.md) collection|Get a list of the [educationOrganization](../resources/educationorganization.md) objects and their properties.|
|[Create educationOrganization](../api/educationorganization-create.md)|[educationOrganization](../resources/educationorganization.md)|Create a new [educationOrganization](../resources/educationorganization.md) object.|
|[Get educationOrganization](../api/educationorganization-get.md)|[educationOrganization](../resources/educationorganization.md)|Read the properties and relationships of an [educationOrganization](../resources/educationorganization.md) object.|
|[Update educationOrganization](../api/educationorganization-update.md)|[educationOrganization](../resources/educationorganization.md)|Update the properties of an [educationOrganization](../resources/educationorganization.md) object.|
|[Delete educationOrganization](../api/educationorganization-delete.md)|None|Deletes an [educationOrganization](../resources/educationorganization.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|externalSource|educationExternalSource|**TODO: Add Description**. Possible values are: `sis`, `manual`, `unknownFutureValue`.|
|externalSourceDetail|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.educationOrganization",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationOrganization",
  "displayName": "String",
  "description": "String",
  "externalSource": "String",
  "externalSourceDetail": "String"
}
```

