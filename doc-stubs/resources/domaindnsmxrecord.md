---
title: "domainDnsMxRecord resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# domainDnsMxRecord resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [domainDnsRecord](../resources/domaindnsrecord.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List domainDnsMxRecords](../api/domaindnsmxrecord-list.md)|[domainDnsMxRecord](../resources/domaindnsmxrecord.md) collection|Get a list of the [domainDnsMxRecord](../resources/domaindnsmxrecord.md) objects and their properties.|
|[Create domainDnsMxRecord](../api/domaindnsmxrecord-create.md)|[domainDnsMxRecord](../resources/domaindnsmxrecord.md)|Create a new [domainDnsMxRecord](../resources/domaindnsmxrecord.md) object.|
|[Get domainDnsMxRecord](../api/domaindnsmxrecord-get.md)|[domainDnsMxRecord](../resources/domaindnsmxrecord.md)|Read the properties and relationships of a [domainDnsMxRecord](../resources/domaindnsmxrecord.md) object.|
|[Update domainDnsMxRecord](../api/domaindnsmxrecord-update.md)|[domainDnsMxRecord](../resources/domaindnsmxrecord.md)|Update the properties of a [domainDnsMxRecord](../resources/domaindnsmxrecord.md) object.|
|[Delete domainDnsMxRecord](../api/domaindnsmxrecord-delete.md)|None|Deletes a [domainDnsMxRecord](../resources/domaindnsmxrecord.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|isOptional|Boolean|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|label|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|mailExchange|String|**TODO: Add Description**|
|preference|Int32|**TODO: Add Description**|
|recordType|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|supportedService|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|ttl|Int32|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.domainDnsMxRecord",
  "baseType": "Microsoft.DirectoryServices.domainDnsRecord",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.domainDnsMxRecord",
  "id": "String (identifier)",
  "isOptional": "Boolean",
  "label": "String",
  "recordType": "String",
  "supportedService": "String",
  "ttl": "Integer",
  "mailExchange": "String",
  "preference": "Integer"
}
```

