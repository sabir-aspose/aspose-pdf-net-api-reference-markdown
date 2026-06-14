---
title: "OpenAIClient.GetRunStepAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific step within a run asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getrunstepasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getrunstepasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:58+00:00"
---
## OpenAIClient.GetRunStepAsync method {#openaiclientgetrunstepasync-method}

Retrieves details of a specific step within a run asynchronously.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run containing the step. |
| runStepId | String | The ID of the run step to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the run step.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run step Id is null or empty. |

### See Also {#see-also}

* class [RunStepResponse](../../runstepresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
