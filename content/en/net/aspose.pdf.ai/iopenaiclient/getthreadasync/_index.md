---
title: "IOpenAIClient.GetThreadAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves details of a specific thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getthreadasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getthreadasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:26+00:00"
---
## IOpenAIClient.GetThreadAsync method {#iopenaiclientgetthreadasync-method}

Retrieves details of a specific thread asynchronously.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the thread.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [ThreadResponse](../../threadresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
