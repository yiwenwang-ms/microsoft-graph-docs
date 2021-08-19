---
title: "domainDnsTxtRecord resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# domainDnsTxtRecord resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [domainDnsRecord](../resources/domaindnsrecord.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List domainDnsTxtRecords](../api/domaindnstxtrecord-list.md)|[domainDnsTxtRecord](../resources/domaindnstxtrecord.md) collection|Get a list of the [domainDnsTxtRecord](../resources/domaindnstxtrecord.md) objects and their properties.|
|[Create domainDnsTxtRecord](../api/domaindnstxtrecord-create.md)|[domainDnsTxtRecord](../resources/domaindnstxtrecord.md)|Create a new [domainDnsTxtRecord](../resources/domaindnstxtrecord.md) object.|
|[Get domainDnsTxtRecord](../api/domaindnstxtrecord-get.md)|[domainDnsTxtRecord](../resources/domaindnstxtrecord.md)|Read the properties and relationships of a [domainDnsTxtRecord](../resources/domaindnstxtrecord.md) object.|
|[Update domainDnsTxtRecord](../api/domaindnstxtrecord-update.md)|[domainDnsTxtRecord](../resources/domaindnstxtrecord.md)|Update the properties of a [domainDnsTxtRecord](../resources/domaindnstxtrecord.md) object.|
|[Delete domainDnsTxtRecord](../api/domaindnstxtrecord-delete.md)|None|Deletes a [domainDnsTxtRecord](../resources/domaindnstxtrecord.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|isOptional|Boolean|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|label|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|recordType|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|supportedService|String|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|
|text|String|**TODO: Add Description**|
|ttl|Int32|**TODO: Add Description** Inherited from [domainDnsRecord](../resources/domaindnsrecord.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.domainDnsTxtRecord",
  "baseType": "Microsoft.DirectoryServices.domainDnsRecord",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.domainDnsTxtRecord",
  "id": "String (identifier)",
  "isOptional": "Boolean",
  "label": "String",
  "recordType": "String",
  "supportedService": "String",
  "ttl": "Integer",
  "text": "String"
}
```

