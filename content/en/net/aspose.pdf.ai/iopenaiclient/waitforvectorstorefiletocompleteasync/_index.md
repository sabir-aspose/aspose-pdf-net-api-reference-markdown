---
title: "IOpenAIClient.WaitForVectorStoreFileToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Waits for a specific vector store file to complete asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:41+00:00"
---
## IOpenAIClient.WaitForVectorStoreFileToCompleteAsync method {#iopenaiclientwaitforvectorstorefiletocompleteasync-method}

Waits for a specific vector store file to complete asynchronously.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the file. |
| fileId | String | The ID of the file to monitor until completion. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the final status of the file.

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
