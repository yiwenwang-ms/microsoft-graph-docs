---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := graphmodels.NewExtension()
additionalData := map[string]interface{}{
	"@odata.context" : "https://graph.microsoft.com/beta/$metadata#users('3fbd929d-8c56-4462-851e-0eb9a7b3a2a5')/extensions/$entity", 
	"xboxGamerTag" : "FierceAdele", 
	"linkedInProfile" : "www.linkedin.com/in/testlinkedinprofile", 
	"id" : "com.contoso.socialSettings", 
}
requestBody.SetAdditionalData(additionalData)

result, err := graphClient.UsersById("user-id").ExtensionsById("extension-id").Get(context.Background(), requestBody, nil)


```