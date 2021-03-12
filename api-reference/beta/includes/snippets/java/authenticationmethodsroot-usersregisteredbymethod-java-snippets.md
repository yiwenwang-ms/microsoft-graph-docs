---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

UserRegistrationMethodSummary userRegistrationMethodSummary = graphClient.reports().authenticationMethods()
	.usersRegisteredByMethod(microsoft.graph.includedUserTypes'all',microsoft.graph.includedUserRoles'all')
	.buildRequest()
	.get();

```