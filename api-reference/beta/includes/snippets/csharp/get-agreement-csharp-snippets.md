---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var agreement = await graphClient.Agreements["{agreement-id}"]
	.Request()
	.Expand("files")
	.GetAsync();

```