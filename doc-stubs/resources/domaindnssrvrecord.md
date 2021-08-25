---
title: "domainDnsSrvRecord resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# domainDnsSrvRecord resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [domainDnsRecord](../resources/domaindnsrecord.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List domainDnsSrvRecords](../api/domaindnssrvrecord-list.md)|[domainDnsSrvRecord](../resources/domaindnssrvrecord.md) collection|Get a list of the [domainDnsSrvRecord](../resources/domaindnssrvrecord.md) objects and their properties.|
|[Create domainDnsSrvRecord](../api/domaindnssrvrecord-create.md)|[domainDnsSrvRecord](../resources/domaindnssrvrecord.md)|Create a new [domainDnsSrvRecord](../resources/domaindnssrvrecord.md) object.|
|[Get domainDnsSrvRecord](../api/domaindnssrvrecord-get.md)|[domainDnsSrvRecord](../resources/domaindnssrvrecord.md)|Read the properties and relationships of a [domainDnsSrvRecord](../resources/domaindnssrvrecord.md) object.|
|[Update domainDnsSrvRecord](../api/domaindnssrvrecord-update.md)|[domainDnsSrvRecord](../resources/domaindnssrvrecord.md)|Update the properties of a [domainDnsSrvRecord](../resources/domaindnssrvrecord.md) object.|
|[Delete domainDnsSrvRecord](../api/domaindnssrvrecord-delete.md)|None|Deletes a [domainDnsSrvRecord](../resources/domaindnssrvrecord.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|isOptional|Boolean|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|label|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|nameTarget|String|**TODO: Add Description**|
|port|Int32|**TODO: Add Description**|
|priority|Int32|**TODO: Add Description**|
|protocol|String|**TODO: Add Description**|
|recordType|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|service|String|**TODO: Add Description**|
|supportedService|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|ttl|Int32|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|weight|Int32|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.domainDnsSrvRecord",
  "baseType": "Microsoft.DirectoryServices.domainDnsRecord",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.domainDnsSrvRecord",
  "id": "String (identifier)",
  "isOptional": "Boolean",
  "label": "String",
  "recordType": "String",
  "supportedService": "String",
  "ttl": "Integer",
  "nameTarget": "String",
  "port": "Integer",
  "priority": "Integer",
  "protocol": "String",
  "service": "String",
  "weight": "Integer"
}
```

