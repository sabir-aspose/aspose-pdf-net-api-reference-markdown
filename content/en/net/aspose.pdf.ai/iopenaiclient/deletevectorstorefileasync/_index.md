---
title: "IOpenAIClient.DeleteVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Deletes a file within a vector store asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:18+00:00"
---
## IOpenAIClient.DeleteVectorStoreFileAsync method {#iopenaiclientdeletevectorstorefileasync-method}

Deletes a file within a vector store asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the file to delete. |
| fileId | String | The ID of the file to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also {#see-also}

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
