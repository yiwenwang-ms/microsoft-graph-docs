---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

EducationAssignmentResource educationAssignmentResource = new EducationAssignmentResource();
educationAssignmentResource.distributeForStudentWork = false;
EducationLinkResource resource = new EducationLinkResource();
resource.displayName = "Bing";
resource.link = "https://www.bing.com";
educationAssignmentResource.resource = resource;

graphClient.education().classes("11021").assignments("19002").resources()
	.buildRequest()
	.post(educationAssignmentResource);

```