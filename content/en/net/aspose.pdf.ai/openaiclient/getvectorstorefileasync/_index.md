---
title: "OpenAIClient.GetVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific file within a vector store asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:03+00:00"
---
## OpenAIClient.GetVectorStoreFileAsync method {#openaiclientgetvectorstorefileasync-method}

Retrieves details of a specific file within a vector store asynchronously.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the file. |
| fileId | String | The ID of the file to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the file.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
