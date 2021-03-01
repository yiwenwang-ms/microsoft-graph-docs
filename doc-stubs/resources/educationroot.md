---
title: "educationRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationRoot resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationRoots](../api/educationroot-list.md)|[educationRoot](../resources/educationroot.md) collection|Get a list of the [educationRoot](../resources/educationroot.md) objects and their properties.|
|[Create educationRoot](../api/educationroot-create.md)|[educationRoot](../resources/educationroot.md)|Create a new [educationRoot](../resources/educationroot.md) object.|
|[Get educationRoot](../api/educationroot-get.md)|[educationRoot](../resources/educationroot.md)|Read the properties and relationships of an [educationRoot](../resources/educationroot.md) object.|
|[Update educationRoot](../api/educationroot-update.md)|[educationRoot](../resources/educationroot.md)|Update the properties of an [educationRoot](../resources/educationroot.md) object.|
|[Delete educationRoot](../api/educationroot-delete.md)|None|Deletes an [educationRoot](../resources/educationroot.md) object.|
|[List synchronizationProfiles](../api/educationroot-list-synchronizationprofiles.md)|[educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) collection|Get the educationSynchronizationProfile resources from the synchronizationProfiles navigation property.|
|[Create educationSynchronizationProfile](../api/educationroot-post-synchronizationprofiles.md)|[educationSynchronizationProfile](../resources/educationsynchronizationprofile.md)|Create a new educationSynchronizationProfile object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|synchronizationProfiles|[educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.educationRoot",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationRoot"
}
```

