---
title: "userConsentRequest resource type"
description: "A userConsentRequest is used for requesting access for an application when the application doesn't have the necessary admin consent."
author: "davidmu1"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
doc_type: resourcePageType
---

# userConsentRequest resource type

Namespace: microsoft.graph

A userConsentRequest is used for requesting access for an application when the application doesn't have the necessary admin consent.

Inherits from [request](../resources/request.md).

## Properties

| Property | Type | Description |
|:---|:---|:---|
| createdBy | [userIdentity](../resources/useridentity.md) | The user who created the request. |
| createdDateTime | DateTimeOffset | The date when the request was created. |
| id | String | The identifier of a request. |
| reason | String |reason for creating this request. |

## Relationships

| Relationship | Type | Description |
|:---|:---|:---|
| approval | [approval](../resources/approval.md) | Used to obtain approval. Inherited from [request](../resources/request.md)|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.userConsentRequest",
  "baseType": "microsoft.graph.request",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userConsentRequest",
  "id": "String (identifier)",
  "reason": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "createdDateTime": "String (timestamp)"
}
```