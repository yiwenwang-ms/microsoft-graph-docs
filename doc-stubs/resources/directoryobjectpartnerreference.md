---
title: "directoryObjectPartnerReference resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# directoryObjectPartnerReference resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [directoryObject](../resources/directoryobject.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List directoryObjectPartnerReferences](../api/directoryobjectpartnerreference-list.md)|[directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md) collection|Get a list of the [directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md) objects and their properties.|
|[Create directoryObjectPartnerReference](../api/directoryobjectpartnerreference-create.md)|[directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md)|Create a new [directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md) object.|
|[Get directoryObjectPartnerReference](../api/directoryobjectpartnerreference-get.md)|[directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md)|Read the properties and relationships of a [directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md) object.|
|[Update directoryObjectPartnerReference](../api/directoryobjectpartnerreference-update.md)|[directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md)|Update the properties of a [directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md) object.|
|[Delete directoryObjectPartnerReference](../api/directoryobjectpartnerreference-delete.md)|None|Deletes a [directoryObjectPartnerReference](../resources/directoryobjectpartnerreference.md) object.|
|[checkMemberGroups](../api/directoryobjectpartnerreference-checkmembergroups.md)|String collection|**TODO: Add Description**|
|[checkMemberObjects](../api/directoryobjectpartnerreference-checkmemberobjects.md)|String collection|**TODO: Add Description**|
|[getMemberGroups](../api/directoryobjectpartnerreference-getmembergroups.md)|String collection|**TODO: Add Description**|
|[getMemberObjects](../api/directoryobjectpartnerreference-getmemberobjects.md)|String collection|**TODO: Add Description**|
|[restore](../api/directoryobjectpartnerreference-restore.md)|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|externalPartnerTenantId|Guid|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|objectType|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.directoryObjectPartnerReference",
  "baseType": "Microsoft.DirectoryServices.directoryObject",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.directoryObjectPartnerReference",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "externalPartnerTenantId": "Guid",
  "objectType": "String"
}
```

