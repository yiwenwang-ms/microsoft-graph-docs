---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var assignmentCategories = await graphClient.Education.Classes["{id}"].AssignmentCategories
	.Request()
	.GetAsync();

```