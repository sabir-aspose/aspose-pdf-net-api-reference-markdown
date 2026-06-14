---
title: "OpenAIClient.CreateVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Creates a new vector store file asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:43+00:00"
---
## OpenAIClient.CreateVectorStoreFileAsync method {#openaiclientcreatevectorstorefileasync-method}

Creates a new vector store file asynchronously.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store where the file will be created. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | The request object containing details for creating the file. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the file creation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also {#see-also}

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
