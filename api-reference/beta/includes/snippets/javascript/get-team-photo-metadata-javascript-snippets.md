---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let profilePhoto = await client.api('/teams/{id}/photo')
	.version('beta')
	.get();

```