---
title: "IOpenAIClient.ModifyThreadAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Modifies an existing thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:34+00:00"
---
## IOpenAIClient.ModifyThreadAsync method {#iopenaiclientmodifythreadasync-method}

Modifies an existing thread asynchronously.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to modify. |
| threadModifyRequest | ThreadModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the thread modification.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [ThreadResponse](../../threadresponse/)
* class [ThreadModifyRequest](../../threadmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
