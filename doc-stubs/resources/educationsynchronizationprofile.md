---
title: "educationSynchronizationProfile resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationSynchronizationProfile resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationSynchronizationProfiles](../api/educationsynchronizationprofile-list.md)|[educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) collection|Get a list of the [educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) objects and their properties.|
|[Create educationSynchronizationProfile](../api/educationsynchronizationprofile-create.md)|[educationSynchronizationProfile](../resources/educationsynchronizationprofile.md)|Create a new [educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) object.|
|[Get educationSynchronizationProfile](../api/educationsynchronizationprofile-get.md)|[educationSynchronizationProfile](../resources/educationsynchronizationprofile.md)|Read the properties and relationships of an [educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) object.|
|[Update educationSynchronizationProfile](../api/educationsynchronizationprofile-update.md)|[educationSynchronizationProfile](../resources/educationsynchronizationprofile.md)|Update the properties of an [educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) object.|
|[Delete educationSynchronizationProfile](../api/educationsynchronizationprofile-delete.md)|None|Deletes an [educationSynchronizationProfile](../resources/educationsynchronizationprofile.md) object.|
|[resume](../api/educationsynchronizationprofile-resume.md)|None|**TODO: Add Description**|
|[pause](../api/educationsynchronizationprofile-pause.md)|None|**TODO: Add Description**|
|[reset](../api/educationsynchronizationprofile-reset.md)|None|**TODO: Add Description**|
|[start](../api/educationsynchronizationprofile-start.md)|[educationFileSynchronizationVerificationMessage](../resources/educationfilesynchronizationverificationmessage.md) collection|**TODO: Add Description**|
|[uploadUrl](../api/educationsynchronizationprofile-uploadurl.md)|String|**TODO: Add Description**|
|[List errors](../api/educationsynchronizationprofile-list-errors.md)|[educationSynchronizationError](../resources/educationsynchronizationerror.md) collection|Get the educationSynchronizationError resources from the errors navigation property.|
|[Create educationSynchronizationError](../api/educationsynchronizationprofile-post-errors.md)|[educationSynchronizationError](../resources/educationsynchronizationerror.md)|Create a new educationSynchronizationError object.|
|[List educationSynchronizationProfileStatus](../api/educationsynchronizationprofile-list-profilestatus.md)|[educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md) collection|Get the educationSynchronizationProfileStatus resources from the profileStatus navigation property.|
|[Create educationSynchronizationProfileStatus](../api/educationsynchronizationprofile-post-profilestatus.md)|[educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md)|Create a new educationSynchronizationProfileStatus object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|dataProvider|[educationSynchronizationDataProvider](../resources/educationsynchronizationdataprovider.md)|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|expirationDate|Date|**TODO: Add Description**|
|handleSpecialCharacterConstraint|Boolean|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|identitySynchronizationConfiguration|[educationIdentitySynchronizationConfiguration](../resources/educationidentitysynchronizationconfiguration.md)|**TODO: Add Description**|
|licensesToAssign|[educationSynchronizationLicenseAssignment](../resources/educationsynchronizationlicenseassignment.md) collection|**TODO: Add Description**|
|state|educationSynchronizationProfileState|**TODO: Add Description**. Possible values are: `deleting`, `deletionFailed`, `provisioningFailed`, `provisioned`, `provisioning`, `unknownFutureValue`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|errors|[educationSynchronizationError](../resources/educationsynchronizationerror.md) collection|**TODO: Add Description**|
|profileStatus|[educationSynchronizationProfileStatus](../resources/educationsynchronizationprofilestatus.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.educationSynchronizationProfile",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationSynchronizationProfile",
  "displayName": "String",
  "expirationDate": "Date",
  "dataProvider": {
    "@odata.type": "microsoft.graph.educationSynchronizationDataProvider"
  },
  "identitySynchronizationConfiguration": {
    "@odata.type": "microsoft.graph.educationIdentitySynchronizationConfiguration"
  },
  "licensesToAssign": [
    {
      "@odata.type": "microsoft.graph.educationSynchronizationLicenseAssignment"
    }
  ],
  "state": "String",
  "handleSpecialCharacterConstraint": "Boolean",
  "id": "String (identifier)"
}
```

