---
title: "IOpenAIClient.UploadFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Uploads a file asynchronously to the OpenAI server"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:38+00:00"
---
## IOpenAIClient.UploadFileAsync method {#iopenaiclientuploadfileasync-method}

Uploads a file asynchronously to the OpenAI server.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| purpose | String | The purpose of the file upload, typically describing how the file will be used. |
| fileName | String | The name of the file to upload. |
| fileBytes | Byte[] | The byte array containing the file data. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the file upload.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the file purpose is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the file name is null or empty. |

### See Also {#see-also}

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
