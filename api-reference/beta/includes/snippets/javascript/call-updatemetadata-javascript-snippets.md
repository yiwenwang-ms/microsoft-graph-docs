---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const updateMetadata = {
  metadata: 'metadata-value',
  clientContext: 'clientContext-value'
};

await client.api('/communications/calls/{id}/updateMetadata')
	.version('beta')
	.post(updateMetadata);

```