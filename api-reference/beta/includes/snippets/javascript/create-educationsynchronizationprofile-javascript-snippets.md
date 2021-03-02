---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const educationSynchronizationProfile = {
    displayName: 'Test Profile',
    dataProvider: {
        '@odata.type': '#Microsoft.Education.DataSync.educationCsvDataProvider',
        customizations: {
            student: {
                optionalPropertiesToSync: [
                    'State ID',
                    'Middle Name'
                ]
            }
        }
    },
    identitySynchronizationConfiguration: {
        '@odata.type': '#Microsoft.Education.DataSync.educationIdentityCreationConfiguration',
        userDomains: [
            {
                appliesTo: 'student',
                name: 'testschool.edu'
            },
            {
                appliesTo: 'teacher',
                name: 'testschool.edu'
            }
        ]
    },
    licensesToAssign: [
        {
            appliesTo: 'teacher',
            skuIds: [
                '6fd2c87f-b296-42f0-b197-1e91e994b900'
            ]
        },
        {
            appliesTo: 'student',
            skuIds: [
                '6fd2c87f-b296-42f0-b197-1e91e994b900'
            ]
        }
    ]
};

await client.api('/education/synchronizationProfiles')
	.version('beta')
	.post(educationSynchronizationProfile);

```