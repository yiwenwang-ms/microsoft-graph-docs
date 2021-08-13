---
title: "invokeUserFlowListener resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# invokeUserFlowListener resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [authenticationListener](../resources/authenticationlistener.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List invokeUserFlowListeners](../api/invokeuserflowlistener-list.md)|[invokeUserFlowListener](../resources/invokeuserflowlistener.md) collection|Get a list of the [invokeUserFlowListener](../resources/invokeuserflowlistener.md) objects and their properties.|
|[Create invokeUserFlowListener](../api/invokeuserflowlistener-create.md)|[invokeUserFlowListener](../resources/invokeuserflowlistener.md)|Create a new [invokeUserFlowListener](../resources/invokeuserflowlistener.md) object.|
|[Get invokeUserFlowListener](../api/invokeuserflowlistener-get.md)|[invokeUserFlowListener](../resources/invokeuserflowlistener.md)|Read the properties and relationships of an [invokeUserFlowListener](../resources/invokeuserflowlistener.md) object.|
|[Update invokeUserFlowListener](../api/invokeuserflowlistener-update.md)|[invokeUserFlowListener](../resources/invokeuserflowlistener.md)|Update the properties of an [invokeUserFlowListener](../resources/invokeuserflowlistener.md) object.|
|[Delete invokeUserFlowListener](../api/invokeuserflowlistener-delete.md)|None|Deletes an [invokeUserFlowListener](../resources/invokeuserflowlistener.md) object.|
|[List b2xIdentityUserFlow](../api/invokeuserflowlistener-list-userflow.md)|[b2xIdentityUserFlow](../resources/b2xidentityuserflow.md) collection|Get the b2xIdentityUserFlow resources from the userFlow navigation property.|
|[Add b2xIdentityUserFlow](../api/invokeuserflowlistener-post-userflow.md)|[b2xIdentityUserFlow](../resources/b2xidentityuserflow.md)|Add userFlow by posting to the userFlow collection.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [authenticationListener](../resources/authenticationlistener.md).|
|priority|Int32|**TODO: Add Description** Inherited from [authenticationListener](../resources/authenticationlistener.md).|
|sourceFilter|[authenticationSourceFilter](../resources/authenticationsourcefilter.md)|**TODO: Add Description** Inherited from [authenticationListener](../resources/authenticationlistener.md).|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|userFlow|[b2xIdentityUserFlow](../resources/b2xidentityuserflow.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.invokeUserFlowListener",
  "baseType": "Microsoft.Cpim.Api.DataModels.authenticationListener",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.invokeUserFlowListener",
  "id": "String (identifier)",
  "priority": "Integer",
  "sourceFilter": {
    "@odata.type": "microsoft.graph.authenticationSourceFilter"
  }
}
```

