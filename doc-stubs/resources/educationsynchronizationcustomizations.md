---
title: "educationSynchronizationCustomizations resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationSynchronizationCustomizations resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [educationSynchronizationCustomizationsBase](../resources/educationsynchronizationcustomizationsbase.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|school|[educationSynchronizationCustomization](../resources/educationsynchronizationcustomization.md)|**TODO: Add Description**|
|section|[educationSynchronizationCustomization](../resources/educationsynchronizationcustomization.md)|**TODO: Add Description**|
|student|[educationSynchronizationCustomization](../resources/educationsynchronizationcustomization.md)|**TODO: Add Description**|
|studentEnrollment|[educationSynchronizationCustomization](../resources/educationsynchronizationcustomization.md)|**TODO: Add Description**|
|teacher|[educationSynchronizationCustomization](../resources/educationsynchronizationcustomization.md)|**TODO: Add Description**|
|teacherRoster|[educationSynchronizationCustomization](../resources/educationsynchronizationcustomization.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.educationSynchronizationCustomizations"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationSynchronizationCustomizations",
  "school": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomization"
  },
  "section": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomization"
  },
  "student": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomization"
  },
  "teacher": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomization"
  },
  "studentEnrollment": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomization"
  },
  "teacherRoster": {
    "@odata.type": "microsoft.graph.educationSynchronizationCustomization"
  }
}
```

