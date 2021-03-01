---
title: "educationPowerSchoolDataProvider resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationPowerSchoolDataProvider resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [educationSynchronizationDataProvider](../resources/educationsynchronizationdataprovider.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowTeachersInMultipleSchools|Boolean|**TODO: Add Description**|
|clientId|String|**TODO: Add Description**|
|clientSecret|String|**TODO: Add Description**|
|connectionUrl|String|**TODO: Add Description**|
|customizations|[educationSynchronizationCustomizations](../resources/educationsynchronizationcustomizations.md)|**TODO: Add Description**|
|schoolsIds|String collection|**TODO: Add Description**|
|schoolYear|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.educationPowerSchoolDataProvider"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationPowerSchoolDataProvider",
  "connectionUrl": "String",
  "clientId": "String",
  "clientSecret": "String",
  "schoolsIds": [
    "String"
  ],
  "schoolYear": "String",
  "allowTeachersInMultipleSchools": "Boolean",
  "customizations": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomizations"
  }
}
```

