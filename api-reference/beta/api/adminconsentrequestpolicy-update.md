---
title: "Update adminConsentRequestPolicy"
description: "Update the properties of an adminConsentRequestPolicy object."
author: "davidmu1"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
doc_type: apiPageType
---

# Update adminConsentRequestPolicy

Namespace: microsoft.graph

Update the properties of an [adminConsentRequestPolicy](../resources/adminconsentrequestpolicy.md) object.

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

| Permission type | Permissions (from most to least privileged) |
|:---|:---|
| Delegated (work or school account) | Policy.ReadWrite.ConsentRequest |
| Delegated (personal Microsoft account) | Not supported. |
| Application | Not supported. |

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PUT /policies/adminConsentRequestPolicy
```

## Request headers

| Name | Description |
|:---|:---|
| Authorization | Bearer {token}. Required. |
| Content-Type | application/json. Required. |

## Request body

In the request body, supply a JSON representation of the [adminConsentRequestPolicy](../resources/adminconsentrequestpolicy.md) object.

The following table shows the properties that are required when you create the [adminConsentRequestPolicy](../resources/adminconsentrequestpolicy.md).

| Property | Type | Description |
|:---|:---|:---|
| isEnabled | Boolean | Indicates whether the admin consent feature is enabled or disabled. |
| notifyReviewers | Boolean | Indicates whether notification to requestors is enabled or disabled. |
| remindersEnabled | Boolean | Indicates whether reminder emails to reviewers is enabled or disabled. |
| requestDurationInDays | Int32 |  Specifies the duration of the request. |
| reviewers | [accessReviewScope](../resources/accessreviewscope.md) collection | Contains the list of reviewers for admin consent. |

## Response

If successful, this method returns a `204 No Content` response code.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_adminconsentrequestpolicy"
}
-->
``` http
PUT https://graph.microsoft.com/beta/policies/adminConsentRequestPolicy
Content-Type: application/json

{
  "@odata.context": "https://graph.microsoft.com/beta/$metadata#policies/adminConsentRequestPolicy/$entity",
  "isEnabled": true,
  "notifyReviewers": true,
  "remindersEnabled": true,
  "requestDurationInDays": 15,
  "reviewers": [
    {
      "query": "/users/02b7b641-2c01-4bd4-bd5e-8ec618a9fbfd",
      "queryType": "MicrosoftGraph"
    }
  ]
}
```

### Response

<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 204 No Content
Content-Type: application/json
```
