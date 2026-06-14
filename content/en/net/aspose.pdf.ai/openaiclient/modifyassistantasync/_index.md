---
title: "OpenAIClient.ModifyAssistantAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Modifies an existing assistant asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/modifyassistantasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/modifyassistantasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:07+00:00"
---
## OpenAIClient.ModifyAssistantAsync method {#openaiclientmodifyassistantasync-method}

Modifies an existing assistant asynchronously.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | String | The ID of the assistant to modify. |
| assistantModifyRequest | AssistantModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the assistant modification.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also {#see-also}

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
