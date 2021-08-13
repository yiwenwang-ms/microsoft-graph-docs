---
title: "authenticationEventsPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# authenticationEventsPolicy resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List authenticationEventsPolicies](../api/authenticationeventspolicy-list.md)|[authenticationEventsPolicy](../resources/authenticationeventspolicy.md) collection|Get a list of the [authenticationEventsPolicy](../resources/authenticationeventspolicy.md) objects and their properties.|
|[Create authenticationEventsPolicy](../api/authenticationeventspolicy-create.md)|[authenticationEventsPolicy](../resources/authenticationeventspolicy.md)|Create a new [authenticationEventsPolicy](../resources/authenticationeventspolicy.md) object.|
|[Get authenticationEventsPolicy](../api/authenticationeventspolicy-get.md)|[authenticationEventsPolicy](../resources/authenticationeventspolicy.md)|Read the properties and relationships of an [authenticationEventsPolicy](../resources/authenticationeventspolicy.md) object.|
|[Update authenticationEventsPolicy](../api/authenticationeventspolicy-update.md)|[authenticationEventsPolicy](../resources/authenticationeventspolicy.md)|Update the properties of an [authenticationEventsPolicy](../resources/authenticationeventspolicy.md) object.|
|[Delete authenticationEventsPolicy](../api/authenticationeventspolicy-delete.md)|None|Deletes an [authenticationEventsPolicy](../resources/authenticationeventspolicy.md) object.|
|[List onSignupStart](../api/authenticationeventspolicy-list-onsignupstart.md)|[authenticationListener](../resources/authenticationlistener.md) collection|Get the authenticationListener resources from the onSignupStart navigation property.|
|[Create authenticationListener](../api/authenticationeventspolicy-post-onsignupstart.md)|[authenticationListener](../resources/authenticationlistener.md)|Create a new authenticationListener object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|onSignupStart|[authenticationListener](../resources/authenticationlistener.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.authenticationEventsPolicy",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.authenticationEventsPolicy",
  "id": "String (identifier)"
}
```

