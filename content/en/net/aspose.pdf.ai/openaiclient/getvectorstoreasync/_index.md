---
title: "OpenAIClient.GetVectorStoreAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific vector store asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:03+00:00"
---
## OpenAIClient.GetVectorStoreAsync method {#openaiclientgetvectorstoreasync-method}

Retrieves details of a specific vector store asynchronously.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the vector store.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
