---
title: "IOpenAIClient.GetAssistantAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves details of a specific assistant asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getassistantasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getassistantasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:19+00:00"
---
## IOpenAIClient.GetAssistantAsync method {#iopenaiclientgetassistantasync-method}

Retrieves details of a specific assistant asynchronously.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | String | The ID of the assistant to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the assistant.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also {#see-also}

* class [AssistantResponse](../../assistantresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
