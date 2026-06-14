---
title: "OpenAIClient.WaitForRunToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Waits for a run to complete within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:14+00:00"
---
## OpenAIClient.WaitForRunToCompleteAsync method {#openaiclientwaitforruntocompleteasync-method}

Waits for a run to complete within a thread asynchronously.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run to monitor until completion. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the final status of the run.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also {#see-also}

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
