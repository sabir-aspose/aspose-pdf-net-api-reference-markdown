---
title: "IOpenAIClient.GetVectorStoresAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of vector stores asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:32+00:00"
---
## IOpenAIClient.GetVectorStoresAsync method {#iopenaiclientgetvectorstoresasync-method}

Retrieves a list of vector stores asynchronously.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Optional query parameters to filter the list of vector stores. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains a list of vector stores.

### See Also {#see-also}

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
