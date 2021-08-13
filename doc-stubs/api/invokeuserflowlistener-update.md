---
title: "Update invokeUserFlowListener"
description: "Update the properties of an invokeUserFlowListener object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update invokeUserFlowListener
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [invokeUserFlowListener](../resources/invokeuserflowlistener.md) object.

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
PATCH /invokeUserFlowListener
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [invokeUserFlowListener](../resources/invokeuserflowlistener.md) object.

The following table shows the properties that are required when you update the [invokeUserFlowListener](../resources/invokeuserflowlistener.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [authenticationListener](../resources/authenticationlistener.md)|
|priority|Int32|**TODO: Add Description** Inherited from [authenticationListener](../resources/authenticationlistener.md)|
|sourceFilter|[Microsoft.Cpim.Api.DataModels.authenticationSourceFilter](../resources/authenticationsourcefilter.md)|**TODO: Add Description** Inherited from [authenticationListener](../resources/authenticationlistener.md)|



## Response

If successful, this method returns a `200 OK` response code and an updated [invokeUserFlowListener](../resources/invokeuserflowlistener.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_invokeuserflowlistener"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/invokeUserFlowListener
Content-Type: application/json
Content-length: 182

{
  "@odata.type": "#microsoft.graph.invokeUserFlowListener",
  "priority": "Integer",
  "sourceFilter": {
    "@odata.type": "microsoft.graph.authenticationSourceFilter"
  }
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
  "@odata.type": "#microsoft.graph.invokeUserFlowListener",
  "id": "f3b3be2f-be2f-f3b3-2fbe-b3f32fbeb3f3",
  "priority": "Integer",
  "sourceFilter": {
    "@odata.type": "microsoft.graph.authenticationSourceFilter"
  }
}
```

