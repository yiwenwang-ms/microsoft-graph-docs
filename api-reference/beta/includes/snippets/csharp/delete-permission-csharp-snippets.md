---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Me.Drive.Root.Items["{UNKNOWN-id}"].Permissions["{UNKNOWN-id}"]
	.Request()
	.DeleteAsync();

```