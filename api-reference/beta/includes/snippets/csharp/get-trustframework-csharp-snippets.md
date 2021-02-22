---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var stream = await graphClient.TrustFramework.Policies["B2C_1A_Test"].Content
	.Request()
	.GetAsync();

```