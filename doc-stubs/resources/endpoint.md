---
title: "endpoint resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# endpoint resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [directoryObject](../resources/directoryobject.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List endpoints](../api/endpoint-list.md)|[endpoint](../resources/endpoint.md) collection|Get a list of the [endpoint](../resources/endpoint.md) objects and their properties.|
|[Create endpoint](../api/endpoint-create.md)|[endpoint](../resources/endpoint.md)|Create a new [endpoint](../resources/endpoint.md) object.|
|[Get endpoint](../api/endpoint-get.md)|[endpoint](../resources/endpoint.md)|Read the properties and relationships of an [endpoint](../resources/endpoint.md) object.|
|[Update endpoint](../api/endpoint-update.md)|[endpoint](../resources/endpoint.md)|Update the properties of an [endpoint](../resources/endpoint.md) object.|
|[Delete endpoint](../api/endpoint-delete.md)|None|Deletes an [endpoint](../resources/endpoint.md) object.|
|[checkMemberGroups](../api/endpoint-checkmembergroups.md)|String collection|**TODO: Add Description**|
|[checkMemberObjects](../api/endpoint-checkmemberobjects.md)|String collection|**TODO: Add Description**|
|[getMemberGroups](../api/endpoint-getmembergroups.md)|String collection|**TODO: Add Description**|
|[getMemberObjects](../api/endpoint-getmemberobjects.md)|String collection|**TODO: Add Description**|
|[restore](../api/endpoint-restore.md)|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|capability|String|**TODO: Add Description**|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|providerId|String|**TODO: Add Description**|
|providerName|String|**TODO: Add Description**|
|providerResourceId|String|**TODO: Add Description**|
|uri|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.endpoint",
  "baseType": "Microsoft.DirectoryServices.directoryObject",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.endpoint",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)",
  "capability": "String",
  "providerId": "String",
  "providerName": "String",
  "uri": "String",
  "providerResourceId": "String"
}
```

