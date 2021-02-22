---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var educationAssignmentResource = new EducationAssignmentResource
{
	DistributeForStudentWork = false,
	Resource = new EducationLinkResource
	{
		DisplayName = "Bing",
		Link = "https://www.bing.com"
	}
};

await graphClient.Education.Classes["11021"].Assignments["19002"].Resources
	.Request()
	.AddAsync(educationAssignmentResource);

```