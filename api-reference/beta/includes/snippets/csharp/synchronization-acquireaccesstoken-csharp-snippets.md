---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var credentials = new List<SynchronizationSecretKeyStringValuePair>()
{
	new Icrosoft.Graph.SynchronizationSecretKeyStringValuePair
	{
	}
};

await graphClient.Applications["{application-id}"].Synchronization
	.AcquireAccessToken(credentials)
	.Request()
	.PostAsync();

```