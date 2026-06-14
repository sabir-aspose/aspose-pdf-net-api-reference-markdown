---
title: "IOpenAIClient.CreateRunAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Creates a run within a specified thread asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/createrunasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/createrunasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:07+00:00"
---
## IOpenAIClient.CreateRunAsync method {#iopenaiclientcreaterunasync-method}

Creates a run within a specified thread asynchronously.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread where the run will be created. |
| runCreateRequest | RunCreateRequest | The request details for creating the run. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the response from the run creation.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also {#see-also}

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
