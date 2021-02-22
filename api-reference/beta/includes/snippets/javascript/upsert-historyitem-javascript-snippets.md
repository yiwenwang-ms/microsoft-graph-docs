---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const activityHistoryItem = {
    startedDateTime: "2015-02-11T20:54:04.3457274+00:00",
    userTimezone: "Africa/Casablanca",
    lastActiveDateTime: "2015-02-11T20:54:04.3457274+00:00"
};

let res = await client.api('/me/activities/13881113971988980728/historyItems/390e06e2-7e5b-4133-8014-fac7ac5991af')
	.version('beta')
	.put(activityHistoryItem);

```