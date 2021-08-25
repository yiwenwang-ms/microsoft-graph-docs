---
title: "domainDnsCnameRecord resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# domainDnsCnameRecord resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [domainDnsRecord](../resources/domaindnsrecord.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List domainDnsCnameRecords](../api/domaindnscnamerecord-list.md)|[domainDnsCnameRecord](../resources/domaindnscnamerecord.md) collection|Get a list of the [domainDnsCnameRecord](../resources/domaindnscnamerecord.md) objects and their properties.|
|[Create domainDnsCnameRecord](../api/domaindnscnamerecord-create.md)|[domainDnsCnameRecord](../resources/domaindnscnamerecord.md)|Create a new [domainDnsCnameRecord](../resources/domaindnscnamerecord.md) object.|
|[Get domainDnsCnameRecord](../api/domaindnscnamerecord-get.md)|[domainDnsCnameRecord](../resources/domaindnscnamerecord.md)|Read the properties and relationships of a [domainDnsCnameRecord](../resources/domaindnscnamerecord.md) object.|
|[Update domainDnsCnameRecord](../api/domaindnscnamerecord-update.md)|[domainDnsCnameRecord](../resources/domaindnscnamerecord.md)|Update the properties of a [domainDnsCnameRecord](../resources/domaindnscnamerecord.md) object.|
|[Delete domainDnsCnameRecord](../api/domaindnscnamerecord-delete.md)|None|Deletes a [domainDnsCnameRecord](../resources/domaindnscnamerecord.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|canonicalName|String|**TODO: Add Description**|
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
  "@odata.type": "microsoft.graph.domainDnsCnameRecord",
  "baseType": "Microsoft.DirectoryServices.domainDnsRecord",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.domainDnsCnameRecord",
  "id": "String (identifier)",
  "isOptional": "Boolean",
  "label": "String",
  "recordType": "String",
  "supportedService": "String",
  "ttl": "Integer",
  "canonicalName": "String"
}
```

