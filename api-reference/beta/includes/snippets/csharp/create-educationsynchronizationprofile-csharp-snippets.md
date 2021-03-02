---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var educationSynchronizationProfile = new EducationSynchronizationProfile
{
	DisplayName = "Test Profile",
	DataProvider = new EducationCsvDataProvider
	{
		Customizations = new EducationSynchronizationCustomizations
		{
			Student = new EducationSynchronizationCustomization
			{
				OptionalPropertiesToSync = new List<String>()
				{
					"State ID",
					"Middle Name"
				}
			}
		}
	},
	IdentitySynchronizationConfiguration = new EducationIdentityCreationConfiguration
	{
		UserDomains = new List<EducationIdentityDomain>()
		{
			new EducationIdentityDomain
			{
				AppliesTo = EducationUserRole.Student,
				Name = "testschool.edu"
			},
			new EducationIdentityDomain
			{
				AppliesTo = EducationUserRole.Teacher,
				Name = "testschool.edu"
			}
		}
	},
	LicensesToAssign = new List<EducationSynchronizationLicenseAssignment>()
	{
		new EducationSynchronizationLicenseAssignment
		{
			AppliesTo = EducationUserRole.Teacher,
			SkuIds = new List<String>()
			{
				"6fd2c87f-b296-42f0-b197-1e91e994b900"
			}
		},
		new EducationSynchronizationLicenseAssignment
		{
			AppliesTo = EducationUserRole.Student,
			SkuIds = new List<String>()
			{
				"6fd2c87f-b296-42f0-b197-1e91e994b900"
			}
		}
	}
};

await graphClient.Education.SynchronizationProfiles
	.Request()
	.AddAsync(educationSynchronizationProfile);

```