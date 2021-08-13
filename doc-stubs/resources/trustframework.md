---
title: "trustFramework resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# trustFramework resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[Get trustFramework](../api/trustframework-get.md)|[trustFramework](../resources/trustframework.md)|Read the properties and relationships of a [trustFramework](../resources/trustframework.md) object.|
|[Update trustFramework](../api/trustframework-update.md)|[trustFramework](../resources/trustframework.md)|Update the properties of a [trustFramework](../resources/trustframework.md) object.|
|[List keySets](../api/trustframework-list-keysets.md)|[trustFrameworkKeySet](../resources/trustframeworkkeyset.md) collection|Get the trustFrameworkKeySet resources from the keySets navigation property.|
|[Create trustFrameworkKeySet](../api/trustframework-post-keysets.md)|[trustFrameworkKeySet](../resources/trustframeworkkeyset.md)|Create a new trustFrameworkKeySet object.|
|[List policies](../api/trustframework-list-policies.md)|[trustFrameworkPolicy](../resources/trustframeworkpolicy.md) collection|Get the trustFrameworkPolicy resources from the policies navigation property.|
|[Create trustFrameworkPolicy](../api/trustframework-post-policies.md)|[trustFrameworkPolicy](../resources/trustframeworkpolicy.md)|Create a new trustFrameworkPolicy object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|keySets|[trustFrameworkKeySet](../resources/trustframeworkkeyset.md) collection|**TODO: Add Description**|
|policies|[trustFrameworkPolicy](../resources/trustframeworkpolicy.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.trustFramework",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.trustFramework",
  "id": "String (identifier)"
}
```

