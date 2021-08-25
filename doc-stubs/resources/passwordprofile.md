---
title: "passwordProfile resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# passwordProfile resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|forceChangePasswordNextSignIn|Boolean|**TODO: Add Description**|
|forceChangePasswordNextSignInWithMfa|Boolean|**TODO: Add Description**|
|password|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.passwordProfile"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.passwordProfile",
  "password": "String",
  "forceChangePasswordNextSignIn": "Boolean",
  "forceChangePasswordNextSignInWithMfa": "Boolean"
}
```

