---
title: "IOpenAIClient.GetFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of files asynchronously based on the specified purpose"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getfilesasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getfilesasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:22+00:00"
---
## IOpenAIClient.GetFilesAsync method {#iopenaiclientgetfilesasync-method}

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
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
