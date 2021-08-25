---
title: "certificateAuthority resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# certificateAuthority resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|certificate|Binary|**TODO: Add Description**|
|certificateRevocationListUrl|String|**TODO: Add Description**|
|deltaCertificateRevocationListUrl|String|**TODO: Add Description**|
|isRootAuthority|Boolean|**TODO: Add Description**|
|issuer|String|**TODO: Add Description**|
|issuerSki|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.certificateAuthority"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.certificateAuthority",
  "isRootAuthority": "Boolean",
  "certificateRevocationListUrl": "String",
  "deltaCertificateRevocationListUrl": "String",
  "certificate": "Binary",
  "issuer": "String",
  "issuerSki": "String"
}
```

