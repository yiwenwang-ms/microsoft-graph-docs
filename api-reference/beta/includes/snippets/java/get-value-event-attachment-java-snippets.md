---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

InputStream stream = graphClient.me().messages("AAMkADVIOAAA=").attachments("AAMkADVIOAAABEgAQACvkutl6c4FMifPyS6NvXsM=").content()
	.buildRequest()
	.get();

```