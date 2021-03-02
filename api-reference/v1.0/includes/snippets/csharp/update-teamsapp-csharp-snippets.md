---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

using var teamsApp = new System.IO.MemoryStream(Encoding.UTF8.GetBytes("[Zip file containing a Teams app package]"));

await graphClient.AppCatalogs.TeamsApps["{teamsApp-id}"]
	.Request()
	.PutAsync(teamsApp);

```