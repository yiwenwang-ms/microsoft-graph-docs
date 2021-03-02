---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IEducationSubmissionResourceCollectionPage submittedResources = graphClient.education().classes("11021").assignments("19002").submissions("850f51b7").submittedResources()
	.buildRequest()
	.get();

```