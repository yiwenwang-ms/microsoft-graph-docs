---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var attachment = new Attachment
{
	Name = "name-value",
	Item = new Message
	{
	}
};

await graphClient.Me.Events["{event-id}"].Attachments
	.Request()
	.AddAsync(attachment);

```