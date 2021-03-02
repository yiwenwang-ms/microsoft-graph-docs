---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var callRecord = await graphClient.Communications.CallRecords["getDirectRoutingCalls(fromDateTime=2019-11-01,toDateTime=2019-12-01)"]
	.Request()
	.GetAsync();

```