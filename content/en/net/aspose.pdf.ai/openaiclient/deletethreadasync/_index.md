---
title: "OpenAIClient.DeleteThreadAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes an existing thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/deletethreadasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/deletethreadasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:47+00:00"
---
## OpenAIClient.DeleteThreadAsync method {#openaiclientdeletethreadasync-method}

Deletes an existing thread asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
