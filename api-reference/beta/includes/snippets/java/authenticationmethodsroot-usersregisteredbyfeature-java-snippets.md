---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

UserRegistrationFeatureSummary userRegistrationFeatureSummary = graphClient.reports().authenticationMethods()
	.usersRegisteredByFeature(microsoft.graph.includedUserTypes'all',microsoft.graph.includedUserRoles'all')
	.buildRequest()
	.get();

```