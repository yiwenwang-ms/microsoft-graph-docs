---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const synchronizationProfiles = {
    displayName: "Test Profile",
    dataProvider: {
        @odata.type: "microsoft.graph.educationcsvdataprovider",
        customizations: {
            student: {
                optionalPropertiesToSync: [
                    "State ID",
                    "Middle Name"
                ]
            }
        }
    },
    identitySynchronizationConfiguration: {
        @odata.type: "microsoft.graph.educationidentitycreationconfiguration",
        userDomains: [
            {
                appliesTo: "student",
                name: "testschool.edu"
            },
            {
                appliesTo: "teacher",
                name: "testschool.edu"
            }
        ]
    },
    licensesToAssign: [
        {
            appliesTo: "teacher",
            skuIds: [
                "6fd2c87f-b296-42f0-b197-1e91e994b900"
            ]
        },
        {
            appliesTo: "student",
            skuIds: [
                "6fd2c87f-b296-42f0-b197-1e91e994b900"
            ]
        }
    ]
};

let res = await client.api('/education/synchronizationProfiles')
	.version('beta')
	.put(synchronizationProfiles);

```