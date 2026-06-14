---
title: "IOpenAIClient.CreateThreadMessageAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Creates a new message within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:10+00:00"
---
## IOpenAIClient.CreateThreadMessageAsync method {#iopenaiclientcreatethreadmessageasync-method}

Creates a new message within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread where the message will be created. |
| threadMessageRequest | ThreadMessageCreateRequest | The request details for creating the message. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the message creation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
