---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)


result, err := graphClient.Admin().Edge().InternetExplorerMode().SiteListsById("browserSiteList-id").SharedCookiesById("browserSharedCookie-id").Get(context.Background(), nil)


```