---
title: "OpenAIClient.ModifyRunAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Modifies an existing run within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/modifyrunasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/modifyrunasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:08+00:00"
---
## OpenAIClient.ModifyRunAsync method {#openaiclientmodifyrunasync-method}

Modifies an existing run within a thread asynchronously.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run to modify. |
| assistantModifyRequest | RunModifyRequest | The request details for modifying the run. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the run modification.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also {#see-also}

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
