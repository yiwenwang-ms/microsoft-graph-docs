---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const educationAssignmentResource = {
  distributeForStudentWork: "false",
  resource: {
    displayName: "Bing",
    link: "https://www.bing.com",
    @odata.type: "#microsoft.education.assignments.api.educationLinkResource"
  }
};

let res = await client.api('/education/classes/11021/assignments/19002/resources')
	.version('beta')
	.post(educationAssignmentResource);

```