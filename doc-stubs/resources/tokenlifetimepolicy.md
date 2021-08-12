---
title: "tokenLifetimePolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# tokenLifetimePolicy resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [stsPolicy](../resources/stspolicy.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List tokenLifetimePolicies](../api/tokenlifetimepolicy-list.md)|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) collection|Get a list of the [tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) objects and their properties.|
|[Create tokenLifetimePolicy](../api/tokenlifetimepolicy-create.md)|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md)|Create a new [tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) object.|
|[Get tokenLifetimePolicy](../api/tokenlifetimepolicy-get.md)|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md)|Read the properties and relationships of a [tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) object.|
|[Update tokenLifetimePolicy](../api/tokenlifetimepolicy-update.md)|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md)|Update the properties of a [tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) object.|
|[Delete tokenLifetimePolicy](../api/tokenlifetimepolicy-delete.md)|None|Deletes a [tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) object.|
|[List appliesTo](../api/tokenlifetimepolicy-list-appliesto.md)|[directoryObject](../resources/directoryobject.md) collection|Get the directoryObject resources from the appliesTo navigation property.|
|[Add appliesTo](../api/tokenlifetimepolicy-post-appliesto.md)|[directoryObject](../resources/directoryobject.md)|Add appliesTo by posting to the appliesTo collection.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|definition|String collection|**TODO: Add Description** Inherited from [stsPolicy](../resources/stspolicy.md).|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|description|String|**TODO: Add Description** Inherited from [policyBase](../resources/policybase.md).|
|displayName|String|**TODO: Add Description** Inherited from [policyBase](../resources/policybase.md).|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|isOrganizationDefault|Boolean|**TODO: Add Description** Inherited from [stsPolicy](../resources/stspolicy.md).|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|appliesTo|[directoryObject](../resources/directoryobject.md) collection|**TODO: Add Description** Inherited from [stsPolicy](../resources/stspolicy.md)|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.tokenLifetimePolicy",
  "baseType": "Microsoft.DirectoryServices.stsPolicy",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.tokenLifetimePolicy",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "definition": [
    "String"
  ],
  "isOrganizationDefault": "Boolean"
}
```

