---
title: "List appConsentRequestsForApproval"
description: "Get the appConsentRequest resources from the appConsentRequestsForApproval navigation property."
author: "davidmu1"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
doc_type: apiPageType
---

# List appConsentRequestsForApproval

Namespace: microsoft.graph

Get the appConsentRequest resources from an appConsentRequestsForApproval.

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

| Permission type | Permissions (from most to least privileged) |
|:---|:---|
| Delegated (work or school account) | ConsentRequest.Read.All, ConsentRequest.ReadWrite.All |
| Delegated (personal Microsoft account)| Not supported. |
| Application | ConsentRequest.Read.All, ConsentRequest.ReadWrite.All |

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /me/appConsentRequestsForApproval/{appConsentRequestsForApproval-id}/userConsentRequests
GET /users/{id}/appConsentRequestsForApproval/{appConsentRequestsForApproval-id}
```

## Optional query parameters

This method supports the `$filter`, `$select`, `$orderBy`, `$skip`, and `$top` OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers

| Name | Description |
|:---|:---|
| Authorization | Bearer {token}. Required. |

## Request body

Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [appConsentRequest](../resources/appconsentrequest.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_appconsentrequest"
}
-->
``` http
GET https://graph.microsoft.com/beta/me/appConsentRequestsForApproval/5a3a0f94-b89d-4cd3-a4ad-fd78faec333f/userConsentRequests
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.appConsentRequest)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.appConsentRequest",
      "id": "60354564-4564-6035-6445-356064453560",
      "appId": "String",
      "appDisplayName": "String",
      "consentType": "String",
      "pendingScopes": [
        {
          "@odata.type": "microsoft.graph.appConsentRequestScope"
        }
      ]
    }
  ]
}
```
