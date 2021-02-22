---
description: "Automatically generated file. DO NOT MODIFY"
---

```objc

MSHTTPClient *httpClient = [MSClientFactory createHTTPClientWithAuthenticationProvider:authenticationProvider];

NSString *MSGraphBaseURL = @"https://graph.microsoft.com/beta/";
NSMutableURLRequest *urlRequest = [NSMutableURLRequest requestWithURL:[NSURL URLWithString:[MSGraphBaseURL stringByAppendingString:@"/me/activities/13881113971988980728/historyItems/390e06e2-7e5b-4133-8014-fac7ac5991af"]]];
[urlRequest setHTTPMethod:@"PUT"];
[urlRequest setValue:@"application/json" forHTTPHeaderField:@"Content-Type"];

MSGraphActivityHistoryItem *activityHistoryItem = [[MSGraphActivityHistoryItem alloc] init];
[activityHistoryItem setStartedDateTime: "2015-02-11T20:54:04.3457274+00:00"];
[activityHistoryItem setUserTimezone:@"Africa/Casablanca"];
[activityHistoryItem setLastActiveDateTime: "2015-02-11T20:54:04.3457274+00:00"];

NSError *error;
NSData *activityHistoryItemData = [activityHistoryItem getSerializedDataWithError:&error];
[urlRequest setHTTPBody:activityHistoryItemData];

MSURLSessionDataTask *meDataTask = [httpClient dataTaskWithRequest:urlRequest 
	completionHandler: ^(NSData *data, NSURLResponse *response, NSError *nserror) {

		//Request Completed

}];

[meDataTask execute];

```