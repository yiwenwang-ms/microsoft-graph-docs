---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var contentInfo = new Microsoft.Graph.ContentInfo
{
	Format = ContentFormat.Default,
	Identifier = null,
	State = ContentState.Rest,
	Metadata = new List<KeyValuePair>()
	{
		new Microsoft.Graph.KeyValuePair
		{
			Name = "MSIP_Label_722a5300-ac39-4c9a-88e3-f54c46676417_Enabled",
			Value = "True"
		},
		new Microsoft.Graph.KeyValuePair
		{
			Name = "MSIP_Label_722a5300-ac39-4c9a-88e3-f54c46676417_Method",
			Value = "Standard"
		},
		new Microsoft.Graph.KeyValuePair
		{
			Name = "MSIP_Label_722a5300-ac39-4c9a-88e3-f54c46676417_SetDate",
			Value = "1/1/0001 12:00:00 AM"
		},
		new Microsoft.Graph.KeyValuePair
		{
			Name = "MSIP_Label_722a5300-ac39-4c9a-88e3-f54c46676417_SiteId",
			Value = "cfa4cf1d-a337-4481-aa99-19d8f3d63f7c"
		},
		new Microsoft.Graph.KeyValuePair
		{
			Name = "MSIP_Label_722a5300-ac39-4c9a-88e3-f54c46676417_Name",
			Value = "Top Secret"
		},
		new Microsoft.Graph.KeyValuePair
		{
			Name = "MSIP_Label_722a5300-ac39-4c9a-88e3-f54c46676417_ContentBits",
			Value = "0"
		},
		new Microsoft.Graph.KeyValuePair
		{
			Name = "MSIP_Label_722a5300-ac39-4c9a-88e3-f54c46676417_ActionId",
			Value = "00000000-0000-0000-0000-000000000000"
		}
	},
	AdditionalData = new Dictionary<string, object>()
	{
		{"format@odata.type", "#microsoft.graph.contentFormat"},
		{"state@odata.type", "#microsoft.graph.contentState"},
		{"metadata@odata.type", "#Collection(microsoft.graph.keyValuePair)"}
	}
};

await graphClient.InformationProtection.Policy.Labels
	.ExtractLabel(contentInfo)
	.Request()
	.Header("User-Agent","ContosoLOBApp/1.0")
	.PostAsync();

```