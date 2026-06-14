---
title: "IOpenAIClient.WaitForThreadMessageToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Waits for a specific thread message to complete asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:40+00:00"
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync method {#iopenaiclientwaitforthreadmessagetocompleteasync-method}

Waits for a specific thread message to complete asynchronously.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the message. |
| threadMessageId | String | The ID of the message to monitor until completion. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the final status of the message.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also {#see-also}

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
