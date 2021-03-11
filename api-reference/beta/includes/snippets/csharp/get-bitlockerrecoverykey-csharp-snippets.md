---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var bitlockerRecoveryKey = await graphClient.Bitlocker.RecoveryKeys["{bitlockerRecoveryKey-id}"]
	.Request()
	.Select("key")
	.GetAsync();

```