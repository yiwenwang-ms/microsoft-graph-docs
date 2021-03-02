---
description: "Automatically generated file. DO NOT MODIFY"
---

```objc

MSHTTPClient *httpClient = [MSClientFactory createHTTPClientWithAuthenticationProvider:authenticationProvider];

NSString *MSGraphBaseURL = @"https://graph.microsoft.com/beta/";
NSMutableURLRequest *urlRequest = [NSMutableURLRequest requestWithURL:[NSURL URLWithString:[MSGraphBaseURL stringByAppendingString:@"/education/synchronizationProfiles"]]];
[urlRequest setHTTPMethod:@"POST"];
[urlRequest setValue:@"application/json" forHTTPHeaderField:@"Content-Type"];

MSGraphEducationSynchronizationProfile *educationSynchronizationProfile = [[MSGraphEducationSynchronizationProfile alloc] init];
[educationSynchronizationProfile setDisplayName:@"Test Profile"];
MSGraphEducationSynchronizationDataProvider *dataProvider = [[MSGraphEducationSynchronizationDataProvider alloc] init];
MSGraphEducationSynchronizationCustomizations *customizations = [[MSGraphEducationSynchronizationCustomizations alloc] init];
MSGraphEducationSynchronizationCustomization *student = [[MSGraphEducationSynchronizationCustomization alloc] init];
NSMutableArray *optionalPropertiesToSyncList = [[NSMutableArray alloc] init];
[optionalPropertiesToSyncList addObject: @"State ID"];
[optionalPropertiesToSyncList addObject: @"Middle Name"];
[student setOptionalPropertiesToSync:optionalPropertiesToSyncList];
[customizations setStudent:student];
[dataProvider setCustomizations:customizations];
[educationSynchronizationProfile setDataProvider:dataProvider];
MSGraphEducationIdentitySynchronizationConfiguration *identitySynchronizationConfiguration = [[MSGraphEducationIdentitySynchronizationConfiguration alloc] init];
NSMutableArray *userDomainsList = [[NSMutableArray alloc] init];
MSGraphEducationIdentityDomain *userDomains = [[MSGraphEducationIdentityDomain alloc] init];
[userDomains setAppliesTo: [MSGraphEducationUserRole student]];
[userDomains setName:@"testschool.edu"];
[userDomainsList addObject: userDomains];
MSGraphEducationIdentityDomain *userDomains = [[MSGraphEducationIdentityDomain alloc] init];
[userDomains setAppliesTo: [MSGraphEducationUserRole teacher]];
[userDomains setName:@"testschool.edu"];
[userDomainsList addObject: userDomains];
[identitySynchronizationConfiguration setUserDomains:userDomainsList];
[educationSynchronizationProfile setIdentitySynchronizationConfiguration:identitySynchronizationConfiguration];
NSMutableArray *licensesToAssignList = [[NSMutableArray alloc] init];
MSGraphEducationSynchronizationLicenseAssignment *licensesToAssign = [[MSGraphEducationSynchronizationLicenseAssignment alloc] init];
[licensesToAssign setAppliesTo: [MSGraphEducationUserRole teacher]];
NSMutableArray *skuIdsList = [[NSMutableArray alloc] init];
[skuIdsList addObject: @"6fd2c87f-b296-42f0-b197-1e91e994b900"];
[licensesToAssign setSkuIds:skuIdsList];
[licensesToAssignList addObject: licensesToAssign];
MSGraphEducationSynchronizationLicenseAssignment *licensesToAssign = [[MSGraphEducationSynchronizationLicenseAssignment alloc] init];
[licensesToAssign setAppliesTo: [MSGraphEducationUserRole student]];
NSMutableArray *skuIdsList = [[NSMutableArray alloc] init];
[skuIdsList addObject: @"6fd2c87f-b296-42f0-b197-1e91e994b900"];
[licensesToAssign setSkuIds:skuIdsList];
[licensesToAssignList addObject: licensesToAssign];
[educationSynchronizationProfile setLicensesToAssign:licensesToAssignList];

NSError *error;
NSData *educationSynchronizationProfileData = [educationSynchronizationProfile getSerializedDataWithError:&error];
[urlRequest setHTTPBody:educationSynchronizationProfileData];

MSURLSessionDataTask *meDataTask = [httpClient dataTaskWithRequest:urlRequest 
	completionHandler: ^(NSData *data, NSURLResponse *response, NSError *nserror) {

		//Request Completed

}];

[meDataTask execute];

```