---
title: "case resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# case resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List cases](../api/case-list.md)|[case](../resources/case.md) collection|Get a list of the [case](../resources/case.md) objects and their properties.|
|[Create case](../api/case-create.md)|[case](../resources/case.md)|Create a new [case](../resources/case.md) object.|
|[Get case](../api/case-get.md)|[case](../resources/case.md)|Read the properties and relationships of a [case](../resources/case.md) object.|
|[Update case](../api/case-update.md)|[case](../resources/case.md)|Update the properties of a [case](../resources/case.md) object.|
|[Delete case](../api/case-delete.md)|None|Deletes a [case](../resources/case.md) object.|
|[List sourceCollections](../api/case-list-sourcecollections.md)|[sourceCollection](../resources/sourcecollection.md) collection|Get the sourceCollection resources from the sourceCollections navigation property.|
|[Create sourceCollection](../api/case-post-sourcecollections.md)|[sourceCollection](../resources/sourcecollection.md)|Create a new sourceCollection object.|
|[List tags](../api/case-list-tags.md)|[tag](../resources/tag.md) collection|Get the tag resources from the tags navigation property.|
|[Create tag](../api/case-post-tags.md)|[tag](../resources/tag.md)|Create a new tag object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|closedDateTime|DateTimeOffset|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|externalId|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|status|caseStatus|**TODO: Add Description**. Possible values are: `unknown`, `active`, `pendingDelete`, `closing`, `closed`, `closedWithError`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|custodians|[custodian](../resources/custodian.md) collection|**TODO: Add Description**|
|legalholds|[legalhold](../resources/legalhold.md) collection|**TODO: Add Description**|
|operations|[caseOperation](../resources/caseoperation.md) collection|**TODO: Add Description**|
|reviewSets|[reviewSet](../resources/reviewset.md) collection|**TODO: Add Description**|
|sourceCollections|[sourceCollection](../resources/sourcecollection.md) collection|**TODO: Add Description**|
|tags|[tag](../resources/tag.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.case",
  "baseType": "microsoft.compliance.ediscovery.contract.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.case",
  "id": "String (identifier)",
  "description": "String",
  "lastModifiedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "lastModifiedDateTime": "String (timestamp)",
  "status": "String",
  "closedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "closedDateTime": "String (timestamp)",
  "externalId": "String",
  "displayName": "String",
  "createdDateTime": "String (timestamp)"
}
```

