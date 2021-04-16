---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var plannerRosterMember = new Microsoft.Graph.PlannerRosterMember
{
	UserId = "String"
};

await graphClient.Planner.Rosters["{plannerRoster-id}"].Members
	.Request()
	.AddAsync(plannerRosterMember);

```