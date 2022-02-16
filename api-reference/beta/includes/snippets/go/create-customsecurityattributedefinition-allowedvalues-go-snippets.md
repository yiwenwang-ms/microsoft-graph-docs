---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewCustomSecurityAttributeDefinition()
attributeSet := "Engineering"
requestBody.SetAttributeSet(&attributeSet)
description := "Active projects for user"
requestBody.SetDescription(&description)
isCollection := true
requestBody.SetIsCollection(&isCollection)
isSearchable := true
requestBody.SetIsSearchable(&isSearchable)
name := "Project"
requestBody.SetName(&name)
status := "Available"
requestBody.SetStatus(&status)
type := "String"
requestBody.SetType(&type)
usePreDefinedValuesOnly := true
requestBody.SetUsePreDefinedValuesOnly(&usePreDefinedValuesOnly)
requestBody.SetAllowedValues( []AllowedValue {
	msgraphsdk.NewAllowedValue(),
	SetAdditionalData(map[string]interface{}{
		"id": "Alpine",
		"isActive": true,
	}
	msgraphsdk.NewAllowedValue(),
	SetAdditionalData(map[string]interface{}{
		"id": "Baker",
		"isActive": true,
	}
	msgraphsdk.NewAllowedValue(),
	SetAdditionalData(map[string]interface{}{
		"id": "Cascade",
		"isActive": true,
	}
}
options := &msgraphsdk.CustomSecurityAttributeDefinitionsRequestBuilderPostOptions{
	Body: requestBody,
}
result, err := graphClient.Directory().CustomSecurityAttributeDefinitions().Post(options)


```