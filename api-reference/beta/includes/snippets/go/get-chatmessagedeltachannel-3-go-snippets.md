---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.DeltaRequestBuilderGetQueryParameters{
	Skiptoken: "8UusBixEHS9UUau6uGcryrA6FpnWwMJbuTYILM1PArHxnZzDVcsHQrijNzCyIVeEauMQsKUfMhNjLWFs1o4sBS_LofJ7xMftZUfec_pijuT6cAk5ugcWCca9RCjK7iVj.DKZ9w4bX9vCR7Sj9P0_qxjLAAPiEZgxlOxxmCLMzHJ4",
}
options := &msgraphsdk.DeltaRequestBuilderGetOptions{
	Q: requestParameters,
}
teamId := "team-id"
channelId := "channel-id"
result, err := graphClient.TeamsById(&teamId).ChannelsById(&channelId).Messages().Delta()().Get(options)


```