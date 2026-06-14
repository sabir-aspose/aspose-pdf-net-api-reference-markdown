---
title: "IOpenAIClient.GetVectorStoreFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of files within a specific vector store asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:31+00:00"
---
## IOpenAIClient.GetVectorStoreFilesAsync method {#iopenaiclientgetvectorstorefilesasync-method}

Retrieves a list of files within a specific vector store asynchronously.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the files. |
| queryParameters | VectorStoreFileListQueryParameters | Optional query parameters to filter the list of files. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains a list of files within the vector store.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
