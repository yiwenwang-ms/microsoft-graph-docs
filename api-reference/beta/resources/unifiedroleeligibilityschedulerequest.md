---
title: "unifiedRoleEligibilityScheduleRequest resource type"
description: "Represents the request for eligible role assignment operations through Azure AD Privileged Identity Management."
author: "shauliu"
localization_priority: Normal
ms.prod: "governance"
doc_type: resourcePageType
---

# unifiedRoleEligibilityScheduleRequest resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents the request for eligible role assignment operations through Azure AD Privileged Identity Management.

`unifiedRoleEligibilityScheduleRequest` is a ticket-modeled entity used to manage the lifecycle of eligible role assignments in the directory. It represents the intention/decision of the users and administrators, and also provides the flexibility to enable implementation of recurrent scheduling, approval gates, and so on, as compared to directly exposing `POST`, `PUT`, and `DELETE` operations on `unifiedRoleEligibilitySchedule` and `unifiedRoleEligibilityInstance`.

Administrators can use `unifiedRoleEligibilityScheduleRequest` to create and/or update eligible role assignments with or without start and end time. While eligible administrators, can use it to create a request to extend or renew their eligible assignments.

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List unifiedRoleEligibilityScheduleRequests](../api/unifiedroleeligibilityschedulerequest-list.md)|[unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md) collection|Get a list of the [unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md) objects and their properties.|
|[Create unifiedRoleEligibilityScheduleRequest](../api/unifiedroleeligibilityschedulerequest-post-unifiedroleeligibilityschedulerequests.md)|[unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md)|Create a new [unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md) object.|
|[Get unifiedRoleEligibilityScheduleRequest](../api/unifiedroleeligibilityschedulerequest-get.md)|[unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md)|Read the properties and relationships of an [unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md) object.|
|[filterByCurrentUser](../api/unifiedroleeligibilityschedulerequest-filterbycurrentuser.md)|[unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md) collection|Get a list of the [unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md) objects and their properties that are related to a particular user.|
|[cancel](../api/unifiedroleeligibilityschedulerequest-cancel.md)|None|Cancels a [unifiedRoleEligibilityScheduleRequest](../resources/unifiedroleeligibilityschedulerequest.md) immediately and marks it for deletion in 30 days|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|action|String|Representing the type of the operation on the role assignment. The value can be <ul><li>`AdminAdd`: Administrators assign users/groups to roles;</li><li>`UserAdd`: Users activate eligible assignments;</li><li> `AdminUpdate`: Administrators change existing role assignments</li><li>`AdminRemove`: Administrators remove users/groups from roles;<li>`UserRemove`: Users deactivate active assignments;<li>`UserExtend`: Users request to extend their expiring assignments;</li><li>`AdminExtend`: Administrators extend expiring assignments.</li><li>`UserRenew`: Users request to renew their expired assignments;</li><li>`AdminRenew`: Administrators extend expiring assignments.</li></ul>|
|appScopeId|String|Id of the app specific scope when the assignment scope is app specific. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use "/" for tenant-wide scope. App scopes are scopes that are defined and understood by this application only.|
|directoryScopeId|String|Id of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. App scopes are scopes that are defined and understood by this application only.|
|id|String|The unique identifier for the unifiedRoleEligibilityScheduleRequest.|
|isValidationOnly|Boolean|A boolean that determines whether the call is a validation or an actual call. Only set this property if you want to check whether an activation is subject to additional rules like MFA before actually submitting the request.|
|justification|String|A message provided by users and administrators when create the request about why it is needed.|
|principalId|String| Objectid of the principal to which the assignment is being granted to.|
|roleDefinitionId|String|ID of the unifiedRoleDefinition the assignment is for. Read only.|
|scheduleInfo|[requestSchedule](../resources/requestschedule.md)|The schedule object of the role assignment request.|
|targetScheduleId|String|ID of the schedule object attached to the assignment.|
|ticketInfo|[ticketInfo](../resources/ticketinfo.md)|The ticketInfo object attached to the role assignment request which includes details of the ticket number and ticket system.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|appScope|[appScope](../resources/appscope.md)|Read-only property with details of the app specific scope when the assignment scope is app specific. Containment entity.|
|directoryScope|[directoryObject](../resources/directoryobject.md)|Property referencing the directory object that is the scope of the assignment. Provided so that callers can get the directory object using `$expand` at the same time as getting the role assignment. Read-only.|
|principal|[directoryObject](../resources/directoryobject.md)|Property referencing the principal that is getting a role assignment through the request. Provided so that callers can get the principal using `$expand` at the same time as getting the role assignment. Read-only. |
|roleDefinition|[unifiedRoleDefinition](../resources/unifiedroledefinition.md)|Property indicating the roleDefinition the assignment is for. Provided so that callers can get the role definition using `$expand` at the same time as getting the role assignment. roleDefinition.Id will be auto expanded|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.unifiedRoleEligibilityScheduleRequest",
  "openType": false
}
-->
``` json
{
  "id": "String (identifier)",
  "action": "String",
  "principalId": "String",
  "roleDefinitionId": "String",
  "directoryScopeId": "String",
  "appScopeId": "String",
  "isValidationOnly": "Boolean",
  "targetScheduleId": "String",
  "justification": "String",
  "scheduleInfo": {
    "@odata.type": "microsoft.graph.requestSchedule"
  },
  "ticketInfo": {
    "@odata.type": "microsoft.graph.ticketInfo"
  }
}
```

