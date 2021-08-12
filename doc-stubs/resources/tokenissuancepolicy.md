---
title: "tokenIssuancePolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# tokenIssuancePolicy resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [stsPolicy](../resources/stspolicy.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List tokenIssuancePolicies](../api/tokenissuancepolicy-list.md)|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md) collection|Get a list of the [tokenIssuancePolicy](../resources/tokenissuancepolicy.md) objects and their properties.|
|[Create tokenIssuancePolicy](../api/tokenissuancepolicy-create.md)|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md)|Create a new [tokenIssuancePolicy](../resources/tokenissuancepolicy.md) object.|
|[Get tokenIssuancePolicy](../api/tokenissuancepolicy-get.md)|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md)|Read the properties and relationships of a [tokenIssuancePolicy](../resources/tokenissuancepolicy.md) object.|
|[Update tokenIssuancePolicy](../api/tokenissuancepolicy-update.md)|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md)|Update the properties of a [tokenIssuancePolicy](../resources/tokenissuancepolicy.md) object.|
|[Delete tokenIssuancePolicy](../api/tokenissuancepolicy-delete.md)|None|Deletes a [tokenIssuancePolicy](../resources/tokenissuancepolicy.md) object.|
|[List appliesTo](../api/tokenissuancepolicy-list-appliesto.md)|[directoryObject](../resources/directoryobject.md) collection|Get the directoryObject resources from the appliesTo navigation property.|
|[Add appliesTo](../api/tokenissuancepolicy-post-appliesto.md)|[directoryObject](../resources/directoryobject.md)|Add appliesTo by posting to the appliesTo collection.|

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
  "@odata.type": "microsoft.graph.tokenIssuancePolicy",
  "baseType": "Microsoft.DirectoryServices.stsPolicy",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.tokenIssuancePolicy",
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

