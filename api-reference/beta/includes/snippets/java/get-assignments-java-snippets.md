---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IEducationCategoryCollectionPage assignmentCategories = graphClient.education().classes("{id}").assignmentCategories()
	.buildRequest()
	.get();

```