---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

serviceUpdateMessageId := "serviceUpdateMessage-id"
graphClient.Admin().ServiceAnnouncement().MessagesById(&serviceUpdateMessageId).AttachmentsArchive().Get(nil)


```