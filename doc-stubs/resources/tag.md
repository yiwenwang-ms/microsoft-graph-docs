---
title: "tag resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# tag resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List tags](../api/tag-list.md)|[tag](../resources/tag.md) collection|Get a list of the [tag](../resources/tag.md) objects and their properties.|
|[Create tag](../api/tag-create.md)|[tag](../resources/tag.md)|Create a new [tag](../resources/tag.md) object.|
|[Get tag](../api/tag-get.md)|[tag](../resources/tag.md)|Read the properties and relationships of a [tag](../resources/tag.md) object.|
|[Update tag](../api/tag-update.md)|[tag](../resources/tag.md)|Update the properties of a [tag](../resources/tag.md) object.|
|[Delete tag](../api/tag-delete.md)|None|Deletes a [tag](../resources/tag.md) object.|
|[asHierarchy](../api/tag-ashierarchy.md)|[tag](../resources/tag.md) collection|**TODO: Add Description**|
|[List childTags](../api/tag-list-childtags.md)|[tag](../resources/tag.md) collection|Get the tag resources from the childTags navigation property.|
|[Add tag](../api/tag-post-childtags.md)|[tag](../resources/tag.md)|Add childTags by posting to the childTags collection.|
|[List tag](../api/tag-list-parent.md)|[tag](../resources/tag.md) collection|Get the tag resources from the parent navigation property.|
|[Add tag](../api/tag-post-parent.md)|[tag](../resources/tag.md)|Add parent by posting to the parent collection.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|childSelectability|childSelectability|**TODO: Add Description**. Possible values are: `One`, `Many`.|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|childTags|[tag](../resources/tag.md) collection|**TODO: Add Description**|
|parent|[tag](../resources/tag.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.tag",
  "baseType": "microsoft.compliance.ediscovery.contract.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.tag",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "childSelectability": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "lastModifiedDateTime": "String (timestamp)"
}
```

