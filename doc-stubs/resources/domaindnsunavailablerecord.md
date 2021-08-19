---
title: "domainDnsUnavailableRecord resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# domainDnsUnavailableRecord resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [domainDnsRecord](../resources/domaindnsrecord.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List domainDnsUnavailableRecords](../api/domaindnsunavailablerecord-list.md)|[domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md) collection|Get a list of the [domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md) objects and their properties.|
|[Create domainDnsUnavailableRecord](../api/domaindnsunavailablerecord-create.md)|[domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md)|Create a new [domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md) object.|
|[Get domainDnsUnavailableRecord](../api/domaindnsunavailablerecord-get.md)|[domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md)|Read the properties and relationships of a [domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md) object.|
|[Update domainDnsUnavailableRecord](../api/domaindnsunavailablerecord-update.md)|[domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md)|Update the properties of a [domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md) object.|
|[Delete domainDnsUnavailableRecord](../api/domaindnsunavailablerecord-delete.md)|None|Deletes a [domainDnsUnavailableRecord](../resources/domaindnsunavailablerecord.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|isOptional|Boolean|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|label|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
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
  "@odata.type": "microsoft.graph.domainDnsUnavailableRecord",
  "baseType": "Microsoft.DirectoryServices.domainDnsRecord",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.domainDnsUnavailableRecord",
  "id": "String (identifier)",
  "isOptional": "Boolean",
  "label": "String",
  "recordType": "String",
  "supportedService": "String",
  "ttl": "Integer",
  "description": "String"
}
```

