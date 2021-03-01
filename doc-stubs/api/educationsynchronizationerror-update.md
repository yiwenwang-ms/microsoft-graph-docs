---
title: "Update educationSynchronizationError"
description: "Update the properties of an educationSynchronizationError object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update educationSynchronizationError
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [educationSynchronizationError](../resources/educationsynchronizationerror.md) object.

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
PATCH /educationRoot/synchronizationProfiles/{educationSynchronizationProfileId}/errors/{educationSynchronizationErrorId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [educationSynchronizationError](../resources/educationsynchronizationerror.md) object.

The following table shows the properties that are required when you update the [educationSynchronizationError](../resources/educationsynchronizationerror.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|entryType|String|**TODO: Add Description**|
|errorCode|String|**TODO: Add Description**|
|errorMessage|String|**TODO: Add Description**|
|joiningValue|String|**TODO: Add Description**|
|recordedDateTime|DateTimeOffset|**TODO: Add Description**|
|reportableIdentifier|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [educationSynchronizationError](../resources/educationsynchronizationerror.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_educationsynchronizationerror"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/educationRoot/synchronizationProfiles/{educationSynchronizationProfileId}/errors/{educationSynchronizationErrorId}
Content-Type: application/json
Content-length: 263

{
  "@odata.type": "#microsoft.graph.educationSynchronizationError",
  "entryType": "String",
  "errorCode": "String",
  "errorMessage": "String",
  "joiningValue": "String",
  "recordedDateTime": "String (timestamp)",
  "reportableIdentifier": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.educationSynchronizationError",
  "id": "bcc5f51b-f51b-bcc5-1bf5-c5bc1bf5c5bc",
  "entryType": "String",
  "errorCode": "String",
  "errorMessage": "String",
  "joiningValue": "String",
  "recordedDateTime": "String (timestamp)",
  "reportableIdentifier": "String"
}
```

