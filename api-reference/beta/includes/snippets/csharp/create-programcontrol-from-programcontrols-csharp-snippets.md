---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new ProgramControl
{
	ControlId = "7e59d237-2fb0-4e5d-b7bb-d4f9f9129213",
	ControlTypeId = "6e4f3d20-c5c3-407f-9695-8460952bcc68",
	ProgramId = "7e59d237-2fb0-4e5d-b7bb-d4f9f9129213",
};
var result = await graphClient.ProgramControls.PostAsync(requestBody);


```