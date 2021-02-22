---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var stream = await graphClient.Me.Messages["AAMkADVIOAAA="].Attachments["AAMkADVIOAAABEgAQACvkutl6c4FMifPyS6NvXsM="].Content
	.Request()
	.GetAsync();

```