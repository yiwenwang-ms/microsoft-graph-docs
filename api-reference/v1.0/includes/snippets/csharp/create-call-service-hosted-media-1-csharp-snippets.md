---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var call = new Microsoft.Graph.Call
{
	CallbackUri = "https://bot.contoso.com/callback",
	Targets = new List<InvitationParticipantInfo>()
	{
		new Microsoft.Graph.InvitationParticipantInfo
		{
			Identity = new Microsoft.Graph.IdentitySet
			{
				User = new Microsoft.Graph.Identity
				{
					DisplayName = "John",
					Id = "112f7296-5fa4-42ca-bae8-6a692b15d4b8"
				}
			}
		}
	},
	RequestedModalities = new List<Modality>()
	{
		Modality.Audio
	},
	MediaConfig = new Microsoft.Graph.ServiceHostedMediaConfig
	{
	}
};

await graphClient.Communications.Calls
	.Request()
	.AddAsync(call);

```