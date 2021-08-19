---
title: "orgContact: delta"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# orgContact: delta
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

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
GET /contacts/delta
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this function returns a `200 OK` response code and a [orgContact](../resources/orgcontact.md) collection in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "orgcontact_delta"
}
-->
``` http
GET https://graph.microsoft.com/beta/contacts/delta
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(Microsoft.DirectoryServices.orgContact)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#Microsoft.DirectoryServices.orgContact",
      "id": "String (identifier)",
      "deletedDateTime": "String (timestamp)",
      "addresses": [
        {
          "@odata.type": "microsoft.graph.physicalOfficeAddress"
        }
      ],
      "companyName": "String",
      "department": "String",
      "displayName": "String",
      "givenName": "String",
      "jobTitle": "String",
      "mail": "String",
      "mailNickname": "String",
      "onPremisesSyncEnabled": "Boolean",
      "onPremisesLastSyncDateTime": "String (timestamp)",
      "onPremisesProvisioningErrors": [
        {
          "@odata.type": "microsoft.graph.onPremisesProvisioningError"
        }
      ],
      "phones": [
        {
          "@odata.type": "microsoft.graph.phone"
        }
      ],
      "proxyAddresses": [
        "String"
      ],
      "surname": "String",
      "cloudMSRtcIsSipEnabled": "Boolean",
      "cloudMSRtcOwnerUrn": "String",
      "cloudMSRtcPolicyAssignments": [
        "String"
      ],
      "cloudMSRtcPool": "String",
      "cloudMSRtcServiceAttribute": {
        "@odata.type": "microsoft.graph.cloudMSRtcServiceAttributes"
      },
      "cloudSipLine": "String"
    }
  ]
}
```

