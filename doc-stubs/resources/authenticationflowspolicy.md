---
title: "authenticationFlowsPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# authenticationFlowsPolicy resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List authenticationFlowsPolicies](../api/authenticationflowspolicy-list.md)|[authenticationFlowsPolicy](../resources/authenticationflowspolicy.md) collection|Get a list of the [authenticationFlowsPolicy](../resources/authenticationflowspolicy.md) objects and their properties.|
|[Create authenticationFlowsPolicy](../api/authenticationflowspolicy-create.md)|[authenticationFlowsPolicy](../resources/authenticationflowspolicy.md)|Create a new [authenticationFlowsPolicy](../resources/authenticationflowspolicy.md) object.|
|[Get authenticationFlowsPolicy](../api/authenticationflowspolicy-get.md)|[authenticationFlowsPolicy](../resources/authenticationflowspolicy.md)|Read the properties and relationships of an [authenticationFlowsPolicy](../resources/authenticationflowspolicy.md) object.|
|[Update authenticationFlowsPolicy](../api/authenticationflowspolicy-update.md)|[authenticationFlowsPolicy](../resources/authenticationflowspolicy.md)|Update the properties of an [authenticationFlowsPolicy](../resources/authenticationflowspolicy.md) object.|
|[Delete authenticationFlowsPolicy](../api/authenticationflowspolicy-delete.md)|None|Deletes an [authenticationFlowsPolicy](../resources/authenticationflowspolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|selfServiceSignUp|[selfServiceSignUpAuthenticationFlowConfiguration](../resources/selfservicesignupauthenticationflowconfiguration.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.authenticationFlowsPolicy",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.authenticationFlowsPolicy",
  "selfServiceSignUp": {
    "@odata.type": "microsoft.graph.selfServiceSignUpAuthenticationFlowConfiguration"
  },
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String"
}
```

