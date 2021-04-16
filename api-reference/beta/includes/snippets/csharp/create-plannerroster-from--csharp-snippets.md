---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var plannerRoster = new Microsoft.Graph.PlannerRoster
{
};

await graphClient.Planner.Rosters
	.Request()
	.AddAsync(plannerRoster);

```