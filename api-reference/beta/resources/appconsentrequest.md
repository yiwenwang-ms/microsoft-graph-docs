---
title: "appConsentRequest resource type"
description: "An appConsentRequest represents an aggregation of userConsentRequest objects."
author: "davidmu1"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
doc_type: resourcePageType
---

# appConsentRequest resource type

Namespace: microsoft.graph

An appConsentRequest represents an aggregation of [userConsentRequest](userConsentrequest.md) objects.

## Methods

| Method | Return type | Description |
|:---|:---|:---|
| [List appConsentRequests](../api/appconsentrequest-list.md) | [appConsentRequest](appconsentrequest.md) collection|Get a list of the [appConsentRequest](appconsentrequest.md) objects and their properties. |
| [Get userConsentRequests](../api/appconsentrequest-get-userconsentrequest.md) | [userConsentRequest](userconsentrequest.md)|Read the properties and relationships of a [userConsentRequest](userconsentrequest.md) object. |


## Properties

| Property | Type | Description |
|:---|:---|:---|
| appDisplayName | String | The app display name of the app consent request. |
| appId | String | The identifier of the application. |
| consentType | String | The consent type of the request. Possible values: `Static` and `Dynamic`. |
| id | String | The identifier of the request. |
| pendingScopes | [accessReviewScope](accessreviewscope.md) collection | A list of pending scopes that need approval. |

## Relationships

| Relationship | Type | Description |
|:---|:---|:---|
| userConsentRequests | [userConsentRequest](userconsentrequest.md) collection | Get a list of pending user consent requests. |

## JSON representation

The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.appConsentRequest",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.appConsentRequest",
  "id": "String (identifier)",
  "appId": "String",
  "appDisplayName": "String",
  "consentType": "String",
  "pendingScopes": [
    {
      "@odata.type": "microsoft.graph.accessReviewScope"
    }
  ]
}
```
