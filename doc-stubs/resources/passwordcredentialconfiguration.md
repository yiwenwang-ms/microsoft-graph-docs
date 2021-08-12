---
title: "passwordCredentialConfiguration resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# passwordCredentialConfiguration resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|maxLifetime|Duration|**TODO: Add Description**|
|restrictForAppsCreatedAfterDateTime|DateTimeOffset|**TODO: Add Description**|
|restrictionType|appCredentialRestrictionType|**TODO: Add Description**. Possible values are: `passwordAddition`, `passwordLifetime`, `unknownFutureValue`, `symmetricKeyAddition`, `symmetricKeyLifetime`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.passwordCredentialConfiguration"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.passwordCredentialConfiguration",
  "restrictionType": "String",
  "maxLifetime": "String (duration)",
  "restrictForAppsCreatedAfterDateTime": "String (timestamp)"
}
```

