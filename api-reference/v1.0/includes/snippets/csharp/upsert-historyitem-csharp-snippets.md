---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var activityHistoryItem = new ActivityHistoryItem
{
	StartedDateTime = DateTimeOffset.Parse("2015-02-11T20:54:04.3457274+00:00"),
	UserTimezone = "Africa/Casablanca",
	LastActiveDateTime = DateTimeOffset.Parse("2015-02-11T20:54:04.3457274+00:00")
};

await graphClient.Me.Activities["{activity-id}"].HistoryItems["{item-id}"]
	.Request()
	.PutAsync(activityHistoryItem);

```