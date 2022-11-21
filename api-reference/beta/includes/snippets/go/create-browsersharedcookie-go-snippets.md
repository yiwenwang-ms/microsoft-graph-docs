---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := graphmodels.NewBrowserSharedCookie()
hostOrDomain := "www.microsoft.com"
requestBody.SetHostOrDomain(&hostOrDomain) 
sourceEnvironment := graphmodels.INTERNETEXPLORER11_BROWSERSHAREDCOOKIESOURCEENVIRONMENT 
requestBody.SetSourceEnvironment(&sourceEnvironment) 
displayName := "Microsoft Cookie"
requestBody.SetDisplayName(&displayName) 
hostOnly := true
requestBody.SetHostOnly(&hostOnly) 
comment := "A cookie for microsoft.com"
requestBody.SetComment(&comment) 
path := "/"
requestBody.SetPath(&path) 

result, err := graphClient.Admin().Edge().InternetExplorerMode().SiteListsById("browserSiteList-id").SharedCookies().Post(context.Background(), requestBody, nil)


```