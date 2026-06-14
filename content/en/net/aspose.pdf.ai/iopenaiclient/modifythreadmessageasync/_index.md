---
title: "IOpenAIClient.ModifyThreadMessageAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Modifies an existing message within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:35+00:00"
---
## IOpenAIClient.ModifyThreadMessageAsync method {#iopenaiclientmodifythreadmessageasync-method}

Modifies an existing message within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the message to modify. |
| threadMessageId | String | The ID of the message to modify. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | The request details for modifying the message. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the message modification.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also {#see-also}

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
