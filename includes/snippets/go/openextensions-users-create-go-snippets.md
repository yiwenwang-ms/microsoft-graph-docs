---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := graphmodels.NewExtension()
additionalData := map[string]interface{}{
	"extensionName" : "com.contoso.roamingSettings", 
	"theme" : "dark", 
	"color" : "purple", 
	"lang" : "Japanese", 
}
requestBody.SetAdditionalData(additionalData)

result, err := graphClient.Me().Extensions().Post(context.Background(), requestBody, nil)


```