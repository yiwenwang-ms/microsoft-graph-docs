---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var driveItem = await graphClient.Drives["{remoteItem-driveId}"].Items["{remoteItem-id}"]
	.Request()
	.GetAsync();

```