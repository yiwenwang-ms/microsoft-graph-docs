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

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationUsers](../api/educationuser-list.md)|[educationUser](../resources/educationuser.md) collection|Get a list of the [educationUser](../resources/educationuser.md) objects and their properties.|
|[Create educationUser](../api/educationuser-create.md)|[educationUser](../resources/educationuser.md)|Create a new [educationUser](../resources/educationuser.md) object.|
|[Get educationUser](../api/educationuser-get.md)|[educationUser](../resources/educationuser.md)|Read the properties and relationships of an [educationUser](../resources/educationuser.md) object.|
|[Update educationUser](../api/educationuser-update.md)|[educationUser](../resources/educationuser.md)|Update the properties of an [educationUser](../resources/educationuser.md) object.|
|[Delete educationUser](../api/educationuser-delete.md)|None|Deletes an [educationUser](../resources/educationuser.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|relatedContacts|[relatedContact](../resources/relatedcontact.md) collection|**TODO: Add Description**|

## Relationships
None.

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
  "id": "String (identifier)",
  "relatedContacts": [
    {
      "@odata.type": "microsoft.graph.relatedContact"
    }
  ]
}
```

