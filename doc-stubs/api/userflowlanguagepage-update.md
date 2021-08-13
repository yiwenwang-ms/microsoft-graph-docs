---
title: "Update userFlowLanguagePage"
description: "Update the properties of a userFlowLanguagePage object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update userFlowLanguagePage
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [userFlowLanguagePage](../resources/userflowlanguagepage.md) object.

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
PATCH /userFlowLanguagePage
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [userFlowLanguagePage](../resources/userflowlanguagepage.md) object.

The following table shows the properties that are required when you update the [userFlowLanguagePage](../resources/userflowlanguagepage.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [userFlowLanguagePage](../resources/userflowlanguagepage.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_userflowlanguagepage"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/userFlowLanguagePage
Content-Type: application/json
Content-length: 62

{
  "@odata.type": "#microsoft.graph.userFlowLanguagePage"
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
  "@odata.type": "#microsoft.graph.userFlowLanguagePage",
  "id": "ae4701c2-01c2-ae47-c201-47aec20147ae"
}
```

