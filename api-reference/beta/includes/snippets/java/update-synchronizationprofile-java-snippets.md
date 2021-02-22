---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

EducationSynchronizationProfile synchronizationProfiles = new EducationSynchronizationProfile();
synchronizationProfiles.displayName = "Test Profile";
Educationcsvdataprovider dataProvider = new Educationcsvdataprovider();
EducationSynchronizationCustomizations customizations = new EducationSynchronizationCustomizations();
EducationSynchronizationCustomization student = new EducationSynchronizationCustomization();
LinkedList<String> optionalPropertiesToSyncList = new LinkedList<String>();
optionalPropertiesToSyncList.add("State ID");
optionalPropertiesToSyncList.add("Middle Name");
student.optionalPropertiesToSync = optionalPropertiesToSyncList;
customizations.student = student;
dataProvider.customizations = customizations;
synchronizationProfiles.dataProvider = dataProvider;
Educationidentitycreationconfiguration identitySynchronizationConfiguration = new Educationidentitycreationconfiguration();
LinkedList<EducationIdentityDomain> userDomainsList = new LinkedList<EducationIdentityDomain>();
EducationIdentityDomain userDomains = new EducationIdentityDomain();
userDomains.appliesTo = EducationUserRole.STUDENT;
userDomains.name = "testschool.edu";
userDomainsList.add(userDomains);
EducationIdentityDomain userDomains1 = new EducationIdentityDomain();
userDomains1.appliesTo = EducationUserRole.TEACHER;
userDomains1.name = "testschool.edu";
userDomainsList.add(userDomains1);
identitySynchronizationConfiguration.userDomains = userDomainsList;
synchronizationProfiles.identitySynchronizationConfiguration = identitySynchronizationConfiguration;
LinkedList<EducationSynchronizationLicenseAssignment> licensesToAssignList = new LinkedList<EducationSynchronizationLicenseAssignment>();
EducationSynchronizationLicenseAssignment licensesToAssign = new EducationSynchronizationLicenseAssignment();
licensesToAssign.appliesTo = EducationUserRole.TEACHER;
LinkedList<String> skuIdsList = new LinkedList<String>();
skuIdsList.add("6fd2c87f-b296-42f0-b197-1e91e994b900");
licensesToAssign.skuIds = skuIdsList;
licensesToAssignList.add(licensesToAssign);
EducationSynchronizationLicenseAssignment licensesToAssign1 = new EducationSynchronizationLicenseAssignment();
licensesToAssign1.appliesTo = EducationUserRole.STUDENT;
LinkedList<String> skuIdsList1 = new LinkedList<String>();
skuIdsList1.add("6fd2c87f-b296-42f0-b197-1e91e994b900");
licensesToAssign1.skuIds = skuIdsList1;
licensesToAssignList.add(licensesToAssign1);
synchronizationProfiles.licensesToAssign = licensesToAssignList;

graphClient.education().synchronizationProfiles()
	.buildRequest()
	.put(synchronizationProfiles);

```