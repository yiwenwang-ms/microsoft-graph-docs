---
title: "userFlowLanguageConfiguration resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# userFlowLanguageConfiguration resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List userFlowLanguageConfigurations](../api/userflowlanguageconfiguration-list.md)|[userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md) collection|Get a list of the [userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md) objects and their properties.|
|[Create userFlowLanguageConfiguration](../api/userflowlanguageconfiguration-create.md)|[userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md)|Create a new [userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md) object.|
|[Get userFlowLanguageConfiguration](../api/userflowlanguageconfiguration-get.md)|[userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md)|Read the properties and relationships of a [userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md) object.|
|[Update userFlowLanguageConfiguration](../api/userflowlanguageconfiguration-update.md)|[userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md)|Update the properties of a [userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md) object.|
|[Delete userFlowLanguageConfiguration](../api/userflowlanguageconfiguration-delete.md)|None|Deletes a [userFlowLanguageConfiguration](../resources/userflowlanguageconfiguration.md) object.|
|[List defaultPages](../api/userflowlanguageconfiguration-list-defaultpages.md)|[userFlowLanguagePage](../resources/userflowlanguagepage.md) collection|Get the userFlowLanguagePage resources from the defaultPages navigation property.|
|[Create userFlowLanguagePage](../api/userflowlanguageconfiguration-post-defaultpages.md)|[userFlowLanguagePage](../resources/userflowlanguagepage.md)|Create a new userFlowLanguagePage object.|
|[List overridesPages](../api/userflowlanguageconfiguration-list-overridespages.md)|[userFlowLanguagePage](../resources/userflowlanguagepage.md) collection|Get the userFlowLanguagePage resources from the overridesPages navigation property.|
|[Create userFlowLanguagePage](../api/userflowlanguageconfiguration-post-overridespages.md)|[userFlowLanguagePage](../resources/userflowlanguagepage.md)|Create a new userFlowLanguagePage object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isEnabled|Boolean|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|defaultPages|[userFlowLanguagePage](../resources/userflowlanguagepage.md) collection|**TODO: Add Description**|
|overridesPages|[userFlowLanguagePage](../resources/userflowlanguagepage.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.userFlowLanguageConfiguration",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userFlowLanguageConfiguration",
  "id": "String (identifier)",
  "isEnabled": "Boolean",
  "displayName": "String"
}
```

