---
title: "OpenAIClient.GetThreadMessagesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves a list of messages for a specific thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:02+00:00"
---
## OpenAIClient.GetThreadMessagesAsync method {#openaiclientgetthreadmessagesasync-method}

Retrieves a list of messages for a specific thread asynchronously.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to retrieve messages from. |
| queryParameters | ThreadMessageListQueryParameters | Optional query parameters to filter the list of messages. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains a list of thread messages.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
