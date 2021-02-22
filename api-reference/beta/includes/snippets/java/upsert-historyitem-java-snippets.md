---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

ActivityHistoryItem activityHistoryItem = new ActivityHistoryItem();
activityHistoryItem.startedDateTime = CalendarSerializer.deserialize("2015-02-11T20:54:04.3457274+00:00");
activityHistoryItem.userTimezone = "Africa/Casablanca";
activityHistoryItem.lastActiveDateTime = CalendarSerializer.deserialize("2015-02-11T20:54:04.3457274+00:00");

graphClient.me().activities("13881113971988980728").historyItems("390e06e2-7e5b-4133-8014-fac7ac5991af")
	.buildRequest()
	.put(activityHistoryItem);

```