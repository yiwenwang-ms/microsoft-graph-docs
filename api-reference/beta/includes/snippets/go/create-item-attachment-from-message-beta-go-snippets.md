---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewAttachment()
name := "Holiday event"
requestBody.SetName(&name)
requestBody.SetAdditionalData(map[string]interface{}{
	"@odata.type": "#microsoft.graph.itemAttachment",
}
options := &msgraphsdk.AttachmentsRequestBuilderPostOptions{
	Body: requestBody,
}
messageId := "message-id"
result, err := graphClient.Me().MessagesById(&messageId).Attachments().Post(options)


```