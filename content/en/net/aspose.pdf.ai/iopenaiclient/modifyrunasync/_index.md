---
title: "IOpenAIClient.ModifyRunAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Modifies an existing run within a thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:34+00:00"
---
## IOpenAIClient.ModifyRunAsync method {#iopenaiclientmodifyrunasync-method}

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
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
