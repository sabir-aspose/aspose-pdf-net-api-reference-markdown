---
title: "IOpenAIClient.DeleteThreadMessageAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Deletes a message within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:17+00:00"
---
## IOpenAIClient.DeleteThreadMessageAsync method {#iopenaiclientdeletethreadmessageasync-method}

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
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
