---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var content = await graphClient.Me.Drive.Items["{item-id}"].Thumbnails["{thumb-id}"]["microsoft.graph.thumbnailSet-id"].Content
	.Request()
	.GetAsync();

```