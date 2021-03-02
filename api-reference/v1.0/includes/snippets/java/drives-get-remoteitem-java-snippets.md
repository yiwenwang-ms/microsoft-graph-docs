---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

DriveItem driveItem = graphClient.drives("{remoteItem-driveId}").items("{remoteItem-id}")
	.buildRequest()
	.get();

```