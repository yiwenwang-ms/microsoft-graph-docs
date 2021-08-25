---
title: "passwordCredential resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# passwordCredential resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|customKeyIdentifier|Binary|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|endDateTime|DateTimeOffset|**TODO: Add Description**|
|hint|String|**TODO: Add Description**|
|keyId|Guid|**TODO: Add Description**|
|secretText|String|**TODO: Add Description**|
|startDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.passwordCredential"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.passwordCredential",
  "customKeyIdentifier": "Binary",
  "endDateTime": "String (timestamp)",
  "keyId": "Guid",
  "startDateTime": "String (timestamp)",
  "secretText": "String",
  "hint": "String",
  "displayName": "String"
}
```

