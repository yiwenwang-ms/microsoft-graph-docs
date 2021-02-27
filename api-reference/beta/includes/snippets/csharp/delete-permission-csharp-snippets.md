---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Me.Drive.Root.Items["UNKNOWN-ID"].Permissions["UNKNOWN-ID"]
	.Request()
	.DeleteAsync();

```