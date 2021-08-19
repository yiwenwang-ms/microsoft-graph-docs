---
title: "tenantAppManagementPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# tenantAppManagementPolicy resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [policyBase](../resources/policybase.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List tenantAppManagementPolicies](../api/tenantappmanagementpolicy-list.md)|[tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md) collection|Get a list of the [tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md) objects and their properties.|
|[Create tenantAppManagementPolicy](../api/tenantappmanagementpolicy-create.md)|[tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md)|Create a new [tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md) object.|
|[Get tenantAppManagementPolicy](../api/tenantappmanagementpolicy-get.md)|[tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md)|Read the properties and relationships of a [tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md) object.|
|[Update tenantAppManagementPolicy](../api/tenantappmanagementpolicy-update.md)|[tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md)|Update the properties of a [tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md) object.|
|[Delete tenantAppManagementPolicy](../api/tenantappmanagementpolicy-delete.md)|None|Deletes a [tenantAppManagementPolicy](../resources/tenantappmanagementpolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|applicationRestrictions|[appManagementConfiguration](../resources/appmanagementconfiguration.md)|**TODO: Add Description**|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|description|String|**TODO: Add Description** Inherited from [policyBase](../resources/policybase.md).|
|displayName|String|**TODO: Add Description** Inherited from [policyBase](../resources/policybase.md).|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md).|
|isEnabled|Boolean|**TODO: Add Description**|
|servicePrincipalRestrictions|[appManagementConfiguration](../resources/appmanagementconfiguration.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.tenantAppManagementPolicy",
  "baseType": "Microsoft.DirectoryServices.policyBase",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.tenantAppManagementPolicy",
  "id": "String (identifier)",
  "deletedDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "isEnabled": "Boolean",
  "applicationRestrictions": {
    "@odata.type": "microsoft.graph.appManagementConfiguration"
  },
  "servicePrincipalRestrictions": {
    "@odata.type": "microsoft.graph.appManagementConfiguration"
  }
}
```

