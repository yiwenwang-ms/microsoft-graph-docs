---
title: "Get userConsentRequests"
description: "Read the properties and relationships of a userConsentRequest object."
author: "davidmu1"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
doc_type: apiPageType
---

# Get userConsentRequests

Namespace: microsoft.graph

Read the properties and relationships of a [userConsentRequest](../resources/userconsentrequest.md) object.

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

| Permission type | Permissions (from most to least privileged) |
|:---|:---|
| Delegated (work or school account) | ConsentRequest.Read.All, ConsentRequest.ReadWrite.All |
| Delegated (personal Microsoft account) | Not supported. |
| Application | ConsentRequest.Read.All, ConsentRequest.ReadWrite.All |

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /identityGovernance/appConsent/appConsentRequests/{id}/userConsentRequests
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

If successful, this method returns a `200 OK` response code and a [userConsentRequest](../resources/userconsentrequest.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_userconsentrequest"
}
-->
``` http
GET https://graph.microsoft.com/beta/identityGovernance/appConsent/appConsentRequests/5a3a0f94-b89d-4cd3-a4ad-fd78faec333f/userConsentRequests
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.userConsentRequest"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.context": "https://graph.microsoft.com/beta/$metadata#userConsentRequests",
  "@odata.count": 1,
  "value": [
    {
      "odata.type": "#microsoft.graph.userConsentRequest",
      "id": "5a3a0f94-b89d-4cd3-a4ad-fd78faec333f",
      "reason": "I need this app for work",
      "createdBy": {
        "user": {
          "id": "a6c7aecb-cbfd-4763-87ef-e91b4bd509d9",
          "displayName": "Contoso user",
          "userPrincipalName": "user1@contoso.com"
        }
      },
      "createdDateTime": "2018-08-03T21:02:30.667Z",
    }
  ]
}
```