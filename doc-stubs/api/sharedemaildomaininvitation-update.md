---
title: "Update sharedEmailDomainInvitation"
description: "Update the properties of a sharedEmailDomainInvitation object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update sharedEmailDomainInvitation
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /domains/{domainsId}/sharedEmailDomainInvitations/{sharedEmailDomainInvitationId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) object.

The following table shows the properties that are required when you update the [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|invitationDomain|String|**TODO: Add Description**|
|invitationStatus|String|**TODO: Add Description**|
|expiryTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [sharedEmailDomainInvitation](../resources/sharedemaildomaininvitation.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_sharedemaildomaininvitation"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/domains/{domainsId}/sharedEmailDomainInvitations/{sharedEmailDomainInvitationId}
Content-Type: application/json
Content-length: 174

{
  "@odata.type": "#microsoft.graph.sharedEmailDomainInvitation",
  "invitationDomain": "String",
  "invitationStatus": "String",
  "expiryTime": "String (timestamp)"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.sharedEmailDomainInvitation",
  "id": "718b7147-7147-718b-4771-8b7147718b71",
  "invitationDomain": "String",
  "invitationStatus": "String",
  "expiryTime": "String (timestamp)"
}
```

