---
title: "OpenAIClient.GetRunStepsAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves a list of steps for a specific run within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getrunstepsasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getrunstepsasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:59+00:00"
---
## OpenAIClient.GetRunStepsAsync method {#openaiclientgetrunstepsasync-method}

Retrieves a list of steps for a specific run within a thread asynchronously.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run to retrieve steps from. |
| queryParameters | RunStepListQueryParameters | Optional query parameters to filter the list of run steps. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the list of run steps.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also {#see-also}

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
