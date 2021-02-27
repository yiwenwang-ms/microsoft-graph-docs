---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let personAnniversary = await client.api('/me/profile/anniversaries/{id}')
	.version('beta')
	.get();

```