---
title: "accessReviewScope resource type"
description: "The appConsentRequestScope contains details of the dynamic permission scopes for which access is being requested."
author: "davidmu1"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
doc_type: resourcePageType
---

# accessReviewScope resource type

Namespace: microsoft.graph

The appConsentRequestScope contains details of the dynamic permission scopes for which access is being requested.

## Properties

| Property | Type | Description |
|:---|:---|:---|
| query | String | The identifier of the reviewer. |
| queryType | String | The type of query. The only value is `MicrosoftGraph`. |

## Relationships

None.

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.accessReviewScope"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessReviewScope",
  "query": "String",
  "queryType": "String"
}
```