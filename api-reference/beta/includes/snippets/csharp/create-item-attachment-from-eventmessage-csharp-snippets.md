---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var attachment = new Microsoft.OutlookServices.ItemAttachment
{
	Name = "name-value",
	Item = new Icrosoft.Graph.Message
	{
	}
};

await graphClient.Me.Events["{event-id}"].Attachments
	.Request()
	.AddAsync(attachment);

```