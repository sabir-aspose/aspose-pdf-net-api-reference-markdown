---
title: "IOpenAIClient.GetVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves details of a specific file within a vector store asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:29+00:00"
---
## IOpenAIClient.GetVectorStoreFileAsync method {#iopenaiclientgetvectorstorefileasync-method}

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
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
