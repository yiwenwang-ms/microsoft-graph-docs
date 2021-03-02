---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var educationCategory = new EducationCategory
{
	DisplayName = "Quizzes"
};

await graphClient.Education.Classes["11019"].AssignmentCategories
	.Request()
	.AddAsync(educationCategory);

```