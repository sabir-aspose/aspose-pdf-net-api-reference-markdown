---
title: "IOpenAIClient.GetRunAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves details of a specific run within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getrunasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getrunasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:22+00:00"
---
## IOpenAIClient.GetRunAsync method {#iopenaiclientgetrunasync-method}

Retrieves details of a specific run within a thread asynchronously.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the run.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also {#see-also}

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
