---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewContentType()
name := "docSet"
requestBody.SetName(&name)
description := "custom docset"
requestBody.SetDescription(&description)
base := msgraphsdk.NewContentType()
requestBody.SetBase(base)
name := "Document Set"
base.SetName(&name)
id := "0x0120D520"
base.SetId(&id)
group := "Document Set Content Types"
requestBody.SetGroup(&group)
options := &msgraphsdk.ContentTypesRequestBuilderPostOptions{
	Body: requestBody,
}
siteId := "site-id"
result, err := graphClient.SitesById(&siteId).ContentTypes().Post(options)


```