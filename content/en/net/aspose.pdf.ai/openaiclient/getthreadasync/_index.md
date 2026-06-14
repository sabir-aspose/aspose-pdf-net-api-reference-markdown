---
title: "OpenAIClient.GetThreadAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getthreadasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getthreadasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:00+00:00"
---
## OpenAIClient.GetThreadAsync method {#openaiclientgetthreadasync-method}

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
