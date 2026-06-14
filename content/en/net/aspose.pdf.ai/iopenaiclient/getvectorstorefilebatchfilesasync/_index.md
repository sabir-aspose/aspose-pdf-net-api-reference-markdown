---
title: "IOpenAIClient.GetVectorStoreFileBatchFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of files within a specific vector store file batch asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:30+00:00"
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync method {#iopenaiclientgetvectorstorefilebatchfilesasync-method}

Retrieves a list of files within a specific vector store file batch asynchronously.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the file batch. |
| fileBatchId | String | The ID of the file batch to retrieve files from. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Optional query parameters to filter the list of files. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains a list of files within the file batch.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store file batch Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
