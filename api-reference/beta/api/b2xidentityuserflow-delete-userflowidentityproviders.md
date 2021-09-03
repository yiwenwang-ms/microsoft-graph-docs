---
title: "Delete a userFlowIdentityProvider"
description: "Delete an identityProvider from a b2xIdentityUserFlow."
ms.localizationpriority: medium
doc_type: apiPageType
author: "namkedia"
ms.prod: "identity-and-sign-in"
---

# Delete a userFlowIdentityProvider

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Delete an identity provider from a [b2xIdentityUserFlow](../resources/b2xidentityuserflow.md) object. For self-service sign up user flows, the values can be `Google-OAUTH` or `Facebook-OAUTH`.

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type      | Permissions (from least to most privileged)              |
|:--------------------|:---------------------------------------------------------|
|Delegated (work or school account)|IdentityUserFlow.ReadWrite.All|
|Delegated (personal Microsoft account)| Not supported.|
|Application| IdentityUserFlow.ReadWrite.All|

The work or school account needs to belong to one of the following roles:

* Global administrator
* External ID user flow administrator

## HTTP request

<!-- { "blockType": "ignored" } -->

```http
DELETE/identity/b2xUserFlows/{userflow-id}/userflowIdentityProviders/{id}/$ref
```

## Request headers

|Name|Description|
|:---------------|:----------|
|Authorization|Bearer {token}. Required.|

## Request body

Do not supply a request body for this method.

## Response

If successful, this method returns a `204 No Content` response code. If unsuccessful, a `4xx` error is returned with the specific error details.

## Example

### Request

The following is an example of the request.


# [HTTP](#tab/http)
<!-- {
  "blockType": "request",
  "name": "delete_b2xUserFlows_userflowIdentityProviders"
}
-->

``` http
DELETE https://graph.microsoft.com/beta/identity/b2xUserFlows/{userflow-id}/userflowIdentityProviders/{identityProvider-id}/$ref
```
# [C#](#tab/csharp)
[!INCLUDE [sample-code](../includes/snippets/csharp/delete-b2xuserflows-userflowidentityproviders-csharp-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [JavaScript](#tab/javascript)
[!INCLUDE [sample-code](../includes/snippets/javascript/delete-b2xuserflows-userflowidentityproviders-javascript-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [Objective-C](#tab/objc)
[!INCLUDE [sample-code](../includes/snippets/objc/delete-b2xuserflows-userflowidentityproviders-objc-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [Java](#tab/java)
[!INCLUDE [sample-code](../includes/snippets/java/delete-b2xuserflows-userflowidentityproviders-java-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

---


### Response

<!-- {
  "blockType": "response",
  "truncated": true
} -->

```http
HTTP/1.1 204 No Content
```
