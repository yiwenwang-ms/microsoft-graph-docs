---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const educationCategory = {
  @odata.id: "https://graph.microsoft.com/v1.0/education/classes/11021/assignmentCategories/ec98f158-341d-4fea-9f8c-14a250d489ac"
};

let res = await client.api('/education/classes/11021/assignments/19002/categories/$ref')
	.version('beta')
	.post(educationCategory);

```