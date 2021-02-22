---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/drives/{remoteItem-driveId}/items/{remoteItem-id}')
	.version('beta')
	.get();

```