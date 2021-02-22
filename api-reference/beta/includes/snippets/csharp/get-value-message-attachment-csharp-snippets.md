---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var stream = await graphClient.Me.Messages["AAMkAGUzY5QKiAAA="].Attachments["AAMkAGUzY5QKiAAABEgAQAK8ktgiIO19OqkvUZAqLmyQ="].Content
	.Request()
	.GetAsync();

```