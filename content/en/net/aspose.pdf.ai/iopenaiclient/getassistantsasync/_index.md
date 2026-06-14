---
title: "IOpenAIClient.GetAssistantsAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of assistants asynchronously"
type: docs
url: "/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:51:20+00:00"
---
## IOpenAIClient.GetAssistantsAsync method {#iopenaiclientgetassistantsasync-method}

Retrieves a list of assistants asynchronously.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Optional query parameters to filter the list of assistants. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value {#return-value}

A task that represents the asynchronous operation. The task result contains the list of assistants.

### See Also {#see-also}

* class [AssistantListResponse](../../assistantlistresponse/)
* class [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
