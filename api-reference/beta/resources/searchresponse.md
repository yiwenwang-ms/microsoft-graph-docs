---
title: "searchResponse resource type"
description: "Description of the searchResponse"
ms.localizationpriority: medium
author: "nmoreau"
ms.prod: "search"
doc_type: "resourcePageType"
---

# searchResponse resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents the response from a search query. 

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|queryAlterationResponse|[alterationResponse](alterationResponse.md)|Provides details of query alteration response for spelling correction.|
|value|[searchResultSet](searchResultSet.md) collection|Represents results from a search query, and the terms used for the query.|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.searchResponse",
  "baseType": null
}-->

```json
{
  "queryAlterationResponse": {"@odata.type": "microsoft.graph.alterationResponse"},
  "value": [{"@odata.type": "microsoft.graph.searchResultSet"}]
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "searchResponse resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->

