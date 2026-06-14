---
title: "OpenAIClient.ModifyVectorStoreAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Modifies an existing vector store asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:11+00:00"
---
## OpenAIClient.ModifyVectorStoreAsync method {#openaiclientmodifyvectorstoreasync-method}

Modifies an existing vector store asynchronously.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store to modify. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the vector store modification.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
