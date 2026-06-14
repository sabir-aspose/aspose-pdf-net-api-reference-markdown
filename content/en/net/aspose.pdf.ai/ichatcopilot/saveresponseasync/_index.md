---
title: "IChatCopilot.SaveResponseAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IChatCopilot method. Asynchronously saves the response for the given message to a PDF file"
type: docs
url: "/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:50:29+00:00"
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Asynchronously saves the response for the given message to a PDF file.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The input message for which the response is saved. |
| outputFileName | String | The name of the output PDF file to save the response. |
| cancellationToken | Nullable`1 | The cancellation token (optional). |

### Return Value {#return-value}

A task representing the asynchronous operation.

### See Also {#see-also}

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Asynchronously saves the response for the given message to a file with specified format.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The input message for which the response is saved. |
| outputFileName | String | The name of the output file to save the response. |
| saveFormat | SaveFormat | The format in which to save the response (PDF if not specified). |
| cancellationToken | Nullable`1 | The cancellation token (optional). |

### Return Value {#return-value-1}

A task representing the asynchronous operation.

### See Also {#see-also-1}

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List<string>, string, CancellationToken?) {#saveresponseasync_1}

Asynchronously saves the responses for the given list of messages to a PDF file.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | The list of input messages for which responses are saved. |
| outputFileName | String | The name of the output PDF file to save the responses. |
| cancellationToken | Nullable`1 | The cancellation token (optional). |

### Return Value {#return-value-2}

A task representing the asynchronous operation.

### See Also {#see-also-2}

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List<string>, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Asynchronously saves the responses for the given list of messages to a file with specified format.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | The list of input messages for which responses are saved. |
| outputFileName | String | The name of the output file to save the responses. |
| saveFormat | SaveFormat | The format in which to save the responses (PDF if not specified). |
| cancellationToken | Nullable`1 | The cancellation token (optional). |

### Return Value {#return-value-3}

A task representing the asynchronous operation.

### See Also {#see-also-3}

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
