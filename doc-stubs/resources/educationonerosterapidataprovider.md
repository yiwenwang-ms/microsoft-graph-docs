---
title: "educationOneRosterApiDataProvider resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationOneRosterApiDataProvider resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [educationSynchronizationDataProvider](../resources/educationsynchronizationdataprovider.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|connectionSettings|[educationSynchronizationConnectionSettings](../resources/educationsynchronizationconnectionsettings.md)|**TODO: Add Description**|
|connectionUrl|String|**TODO: Add Description**|
|customizations|[educationSynchronizationCustomizations](../resources/educationsynchronizationcustomizations.md)|**TODO: Add Description**|
|providerName|String|**TODO: Add Description**|
|schoolsIds|String collection|**TODO: Add Description**|
|termIds|String collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.educationOneRosterApiDataProvider"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationOneRosterApiDataProvider",
  "connectionUrl": "String",
  "connectionSettings": {
    "@odata.type": "microsoft.graph.educationSynchronizationConnectionSettings"
  },
  "schoolsIds": [
    "String"
  ],
  "termIds": [
    "String"
  ],
  "providerName": "String",
  "customizations": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomizations"
  }
}
```

