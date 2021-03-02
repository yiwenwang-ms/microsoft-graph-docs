---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var siteSource = new Microsoft.Graph.Ediscovery.SiteSource
{
	AdditionalData = new Dictionary<string, object>()
	{
		{"site@odata.bind", "https://graph.microsoft.com/v1.0/sites/{siteId}"}
	}
};

await graphClient.Compliance.Ediscovery.Cases["{ediscovery.case-id}"].Custodians["{ediscovery.custodian-id}"].SiteSources
	.Request()
	.AddAsync(siteSource);

```