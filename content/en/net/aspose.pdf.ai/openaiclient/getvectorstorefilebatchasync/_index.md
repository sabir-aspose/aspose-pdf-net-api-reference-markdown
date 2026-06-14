---
title: "OpenAIClient.GetVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific vector store file batch asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:04+00:00"
---
## OpenAIClient.GetVectorStoreFileBatchAsync method {#openaiclientgetvectorstorefilebatchasync-method}

Retrieves details of a specific vector store file batch asynchronously.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the file batch. |
| fileBatchId | String | The ID of the file batch to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the file batch.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store file batch Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
