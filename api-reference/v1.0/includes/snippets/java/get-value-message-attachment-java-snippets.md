---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

InputStream stream = graphClient.me().messages("AAMkAGUzY5QKiAAA=").attachments("AAMkAGUzY5QKiAAABEgAQAK8ktgiIO19OqkvUZAqLmyQ=").content()
	.buildRequest()
	.get();

```