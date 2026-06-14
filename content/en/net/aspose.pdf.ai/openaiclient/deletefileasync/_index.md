---
title: "OpenAIClient.DeleteFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes a specific file asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/deletefileasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/deletefileasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:46+00:00"
---
## OpenAIClient.DeleteFileAsync method {#openaiclientdeletefileasync-method}

Deletes a specific file asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileId | String | The ID of the file to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also {#see-also}

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
