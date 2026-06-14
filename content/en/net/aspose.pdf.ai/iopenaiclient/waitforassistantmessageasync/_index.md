---
title: "IOpenAIClient.WaitForAssistantMessageAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Waits for the first message from the assistant within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:38+00:00"
---
## IOpenAIClient.WaitForAssistantMessageAsync method {#iopenaiclientwaitforassistantmessageasync-method}

Waits for the first message from the assistant within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to monitor for the first assistant message. |
| queryParameters | ThreadMessageListQueryParameters | Optional query parameters to filter the list of messages. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the first assistant message in the thread.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
