---
title: "OpenAIClient.GetFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves a list of files asynchronously based on the specified purpose"
type: docs
url: "/net/aspose.pdf.ai/openaiclient/getfilesasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiclient/getfilesasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:53:54+00:00"
---
## OpenAIClient.GetFilesAsync method {#openaiclientgetfilesasync-method}

Retrieves a list of files asynchronously based on the specified purpose.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| purpose | String | Optional. The purpose of the files to retrieve. If null, files for all purposes are retrieved. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains a list of files.

### See Also {#see-also}

* class [FileListResponse](../../filelistresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
