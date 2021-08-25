---
title: "domainDnsRecord resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# domainDnsRecord resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List domainDnsRecords](../api/domaindnsrecord-list.md)|[domainDnsRecord](../resources/domaindnsrecord.md) collection|Get a list of the [domainDnsRecord](../resources/domaindnsrecord.md) objects and their properties.|
|[Create domainDnsRecord](../api/domaindnsrecord-post-domaindnsrecords.md)|[domainDnsRecord](../resources/domaindnsrecord.md)|Create a new [domainDnsRecord](../resources/domaindnsrecord.md) object.|
|[Get domainDnsRecord](../api/domaindnsrecord-get.md)|[domainDnsRecord](../resources/domaindnsrecord.md)|Read the properties and relationships of a [domainDnsRecord](../resources/domaindnsrecord.md) object.|
|[Update domainDnsRecord](../api/domaindnsrecord-update.md)|[domainDnsRecord](../resources/domaindnsrecord.md)|Update the properties of a [domainDnsRecord](../resources/domaindnsrecord.md) object.|
|[Delete domainDnsRecord](../api/domaindnsrecord-delete.md)|None|Deletes a [domainDnsRecord](../resources/domaindnsrecord.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|isOptional|Boolean|**TODO: Add Description**|
|label|String|**TODO: Add Description**|
|recordType|String|**TODO: Add Description**|
|supportedService|String|**TODO: Add Description**|
|ttl|Int32|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.domainDnsRecord",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.domainDnsRecord",
  "id": "String (identifier)",
  "isOptional": "Boolean",
  "label": "String",
  "recordType": "String",
  "supportedService": "String",
  "ttl": "Integer"
}
```

