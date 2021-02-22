---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IUserActivityCollectionPage activities = graphClient.me().activities()
	.buildRequest()
	.get();

```