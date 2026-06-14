---
title: "OpenAIClient.DeleteThreadMessageAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes a message within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:47+00:00"
---
## OpenAIClient.DeleteThreadMessageAsync method {#openaiclientdeletethreadmessageasync-method}

Deletes a message within a thread asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the message to delete. |
| threadMessageId | String | The ID of the message to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also {#see-also}

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
