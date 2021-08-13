---
title: "identityContainer resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityContainer resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[Get identityContainer](../api/identitycontainer-get.md)|[identityContainer](../resources/identitycontainer.md)|Read the properties and relationships of an [identityContainer](../resources/identitycontainer.md) object.|
|[Update identityContainer](../api/identitycontainer-update.md)|[identityContainer](../resources/identitycontainer.md)|Update the properties of an [identityContainer](../resources/identitycontainer.md) object.|
|[List apiConnectors](../api/identitycontainer-list-apiconnectors.md)|[identityApiConnector](../resources/identityapiconnector.md) collection|Get the identityApiConnector resources from the apiConnectors navigation property.|
|[Create identityApiConnector](../api/identitycontainer-post-apiconnectors.md)|[identityApiConnector](../resources/identityapiconnector.md)|Create a new identityApiConnector object.|
|[List b2cUserFlows](../api/identitycontainer-list-b2cuserflows.md)|[b2cIdentityUserFlow](../resources/b2cidentityuserflow.md) collection|Get the b2cIdentityUserFlow resources from the b2cUserFlows navigation property.|
|[Create b2cIdentityUserFlow](../api/identitycontainer-post-b2cuserflows.md)|[b2cIdentityUserFlow](../resources/b2cidentityuserflow.md)|Create a new b2cIdentityUserFlow object.|
|[List b2xUserFlows](../api/identitycontainer-list-b2xuserflows.md)|[b2xIdentityUserFlow](../resources/b2xidentityuserflow.md) collection|Get the b2xIdentityUserFlow resources from the b2xUserFlows navigation property.|
|[Create b2xIdentityUserFlow](../api/identitycontainer-post-b2xuserflows.md)|[b2xIdentityUserFlow](../resources/b2xidentityuserflow.md)|Create a new b2xIdentityUserFlow object.|
|[List identityProviders](../api/identitycontainer-list-identityproviders.md)|[identityProviderBase](../resources/identityproviderbase.md) collection|Get the identityProviderBase resources from the identityProviders navigation property.|
|[Create identityProviderBase](../api/identitycontainer-post-identityproviders.md)|[identityProviderBase](../resources/identityproviderbase.md)|Create a new identityProviderBase object.|
|[List userFlowAttributes](../api/identitycontainer-list-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md) collection|Get the identityUserFlowAttribute resources from the userFlowAttributes navigation property.|
|[Create identityUserFlowAttribute](../api/identitycontainer-post-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Create a new identityUserFlowAttribute object.|
|[List userFlows](../api/identitycontainer-list-userflows.md)|[identityUserFlow](../resources/identityuserflow.md) collection|Get the identityUserFlow resources from the userFlows navigation property.|
|[Create identityUserFlow](../api/identitycontainer-post-userflows.md)|[identityUserFlow](../resources/identityuserflow.md)|Create a new identityUserFlow object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|apiConnectors|[identityApiConnector](../resources/identityapiconnector.md) collection|**TODO: Add Description**|
|authenticationEventListeners|[authenticationEventListener](../resources/authenticationeventlistener.md) collection|**TODO: Add Description**|
|b2cUserFlows|[b2cIdentityUserFlow](../resources/b2cidentityuserflow.md) collection|**TODO: Add Description**|
|b2xUserFlows|[b2xIdentityUserFlow](../resources/b2xidentityuserflow.md) collection|**TODO: Add Description**|
|events|[authenticationEventsPolicy](../resources/authenticationeventspolicy.md)|**TODO: Add Description**|
|featureConfigurations|[featureConfiguration](../resources/featureconfiguration.md) collection|**TODO: Add Description**|
|identityProviders|[identityProviderBase](../resources/identityproviderbase.md) collection|**TODO: Add Description**|
|userFlowAttributes|[identityUserFlowAttribute](../resources/identityuserflowattribute.md) collection|**TODO: Add Description**|
|userFlows|[identityUserFlow](../resources/identityuserflow.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityContainer",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityContainer",
  "id": "String (identifier)"
}
```

