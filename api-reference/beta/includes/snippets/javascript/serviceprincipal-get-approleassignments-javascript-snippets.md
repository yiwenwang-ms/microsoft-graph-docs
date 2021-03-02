---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let appRoleAssignments = await client.api('/servicePrincipals/{id}/appRoleAssignments')
	.version('beta')
	.get();

```