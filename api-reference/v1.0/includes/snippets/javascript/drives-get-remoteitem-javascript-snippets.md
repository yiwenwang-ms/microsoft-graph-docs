---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let driveItem = await client.api('/drives/{remoteItem-driveId}/items/{remoteItem-id}')
	.get();

```