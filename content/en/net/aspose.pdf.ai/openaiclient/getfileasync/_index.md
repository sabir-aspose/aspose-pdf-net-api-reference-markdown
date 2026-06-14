---
title: "OpenAIClient.GetFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific file asynchronously"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getfileasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getfileasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:53+00:00"
---
## OpenAIClient.GetFileAsync method {#openaiclientgetfileasync-method}

Retrieves details of a specific file asynchronously.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileId | String | The ID of the file to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the details of the file.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also {#see-also}

* class [FileResponse](../../fileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
