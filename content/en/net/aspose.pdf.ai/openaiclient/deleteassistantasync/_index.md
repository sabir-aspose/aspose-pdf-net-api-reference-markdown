---
title: "OpenAIClient.DeleteAssistantAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes an existing assistant asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/deleteassistantasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/deleteassistantasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:45+00:00"
---
## OpenAIClient.DeleteAssistantAsync method {#openaiclientdeleteassistantasync-method}

Deletes an existing assistant asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | String | The ID of the assistant to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also {#see-also}

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
