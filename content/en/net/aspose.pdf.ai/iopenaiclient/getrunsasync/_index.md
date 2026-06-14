---
title: "IOpenAIClient.GetRunsAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of runs for a specified thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getrunsasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getrunsasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:23+00:00"
---
## IOpenAIClient.GetRunsAsync method {#iopenaiclientgetrunsasync-method}

Retrieves a list of runs for a specified thread asynchronously.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to retrieve runs from. |
| queryParameters | RunListQueryParameters | Optional query parameters to filter the list of runs. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains a list of runs.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
