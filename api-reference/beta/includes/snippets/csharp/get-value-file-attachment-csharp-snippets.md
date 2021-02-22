---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var stream = await graphClient.Me.Messages["AAMkAGUzY5QKjAAA="].Attachments["AAMkAGUzY5QKjAAABEgAQAMkpJI_X-LBFgvrv1PlZYd8="].Content
	.Request()
	.GetAsync();

```