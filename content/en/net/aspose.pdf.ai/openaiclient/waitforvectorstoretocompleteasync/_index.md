---
title: "OpenAIClient.WaitForVectorStoreToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Waits for a specific vector store to complete asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:16+00:00"
---
## OpenAIClient.WaitForVectorStoreToCompleteAsync method {#openaiclientwaitforvectorstoretocompleteasync-method}

Waits for a specific vector store to complete asynchronously.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store to monitor until completion. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the final status of the vector store.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
