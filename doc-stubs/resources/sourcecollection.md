---
title: "sourceCollection resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# sourceCollection resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List sourceCollections](../api/sourcecollection-list.md)|[sourceCollection](../resources/sourcecollection.md) collection|Get a list of the [sourceCollection](../resources/sourcecollection.md) objects and their properties.|
|[Create sourceCollection](../api/sourcecollection-create.md)|[sourceCollection](../resources/sourcecollection.md)|Create a new [sourceCollection](../resources/sourcecollection.md) object.|
|[Get sourceCollection](../api/sourcecollection-get.md)|[sourceCollection](../resources/sourcecollection.md)|Read the properties and relationships of a [sourceCollection](../resources/sourcecollection.md) object.|
|[Update sourceCollection](../api/sourcecollection-update.md)|[sourceCollection](../resources/sourcecollection.md)|Update the properties of a [sourceCollection](../resources/sourcecollection.md) object.|
|[Delete sourceCollection](../api/sourcecollection-delete.md)|None|Deletes a [sourceCollection](../resources/sourcecollection.md) object.|
|[estimateStatistics](../api/sourcecollection-estimatestatistics.md)|None|**TODO: Add Description**|
|[List additionalSources](../api/sourcecollection-list-additionalsources.md)|[dataSource](../resources/datasource.md) collection|Get the dataSource resources from the additionalSources navigation property.|
|[Create dataSource](../api/sourcecollection-post-additionalsources.md)|[dataSource](../resources/datasource.md)|Create a new dataSource object.|
|[List addToReviewSetOperation](../api/sourcecollection-list-addtoreviewsetoperation.md)|[addToReviewSetOperation](../resources/addtoreviewsetoperation.md) collection|Get the addToReviewSetOperation resources from the addToReviewSetOperation navigation property.|
|[Add addToReviewSetOperation](../api/sourcecollection-post-addtoreviewsetoperation.md)|[addToReviewSetOperation](../resources/addtoreviewsetoperation.md)|Add addToReviewSetOperation by posting to the addToReviewSetOperation collection.|
|[List custodianSources](../api/sourcecollection-list-custodiansources.md)|[dataSource](../resources/datasource.md) collection|Get the dataSource resources from the custodianSources navigation property.|
|[Add dataSource](../api/sourcecollection-post-custodiansources.md)|[dataSource](../resources/datasource.md)|Add custodianSources by posting to the custodianSources collection.|
|[List estimateStatisticsOperation](../api/sourcecollection-list-lastestimatestatisticsoperation.md)|[estimateStatisticsOperation](../resources/estimatestatisticsoperation.md) collection|Get the estimateStatisticsOperation resources from the lastEstimateStatisticsOperation navigation property.|
|[Add estimateStatisticsOperation](../api/sourcecollection-post-lastestimatestatisticsoperation.md)|[estimateStatisticsOperation](../resources/estimatestatisticsoperation.md)|Add lastEstimateStatisticsOperation by posting to the lastEstimateStatisticsOperation collection.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|contentQuery|String|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|tenantSources|tenantSources|**TODO: Add Description**. Possible values are: `allMailboxes`, `allSites`, `unknownFutureValue`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|additionalSources|[dataSource](../resources/datasource.md) collection|**TODO: Add Description**|
|addToReviewSetOperation|[addToReviewSetOperation](../resources/addtoreviewsetoperation.md)|**TODO: Add Description**|
|custodianSources|[dataSource](../resources/datasource.md) collection|**TODO: Add Description**|
|lastEstimateStatisticsOperation|[estimateStatisticsOperation](../resources/estimatestatisticsoperation.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.sourceCollection",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.sourceCollection",
  "displayName": "String",
  "description": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "createdDateTime": "String (timestamp)",
  "lastModifiedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "lastModifiedDateTime": "String (timestamp)",
  "contentQuery": "String",
  "tenantSources": "String"
}
```

