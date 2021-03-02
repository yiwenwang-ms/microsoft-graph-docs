---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var appRoleAssignment = new AppRoleAssignment
{
	PrincipalId = Guid.Parse("principalId-value"),
	ResourceId = Guid.Parse("resourceId-value"),
	AppRoleId = Guid.Parse("appRoleId-value")
};

await graphClient.ServicePrincipals["{servicePrincipal-id}"].AppRoleAssignedTo
	.Request()
	.AddAsync(appRoleAssignment);

```