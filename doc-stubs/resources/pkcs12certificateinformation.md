---
title: "pkcs12CertificateInformation resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# pkcs12CertificateInformation resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|isActive|Boolean|**TODO: Add Description**|
|notAfter|Int64|**TODO: Add Description**|
|notBefore|Int64|**TODO: Add Description**|
|thumbprint|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.pkcs12CertificateInformation"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.pkcs12CertificateInformation",
  "isActive": "Boolean",
  "thumbprint": "String",
  "notAfter": "Integer",
  "notBefore": "Integer"
}
```

