---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)


result, err := graphClient.Admin().Edge().InternetExplorerMode().SiteListsById("browserSiteList-id").SitesById("browserSite-id").Get(context.Background(), nil)


```