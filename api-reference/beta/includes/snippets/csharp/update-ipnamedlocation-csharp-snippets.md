---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var namedLocation = new Microsoft.Graph.IpNamedLocation
{
	DisplayName = "Untrusted named location with only IPv4 address",
	IsTrusted = false,
	IpRanges = new List<IpRange>()
	{
		new Microsoft.Graph.IPv4CidrRange
		{
			CidrAddress = "6.5.4.3/18"
		}
	}
};

await graphClient.Identity.ConditionalAccess.NamedLocations["{namedLocation-id}"]
	.Request()
	.UpdateAsync(namedLocation);

```