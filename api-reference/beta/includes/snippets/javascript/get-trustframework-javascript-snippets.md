---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let stream = await client.api('/trustFramework/policies/B2C_1A_Test/$value')
	.version('beta')
	.get();

```