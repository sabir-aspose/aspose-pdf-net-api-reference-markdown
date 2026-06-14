---
title: "Interface IChatCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.IChatCopilot interface. Represents a chat copilot for interacting with documents via AI models"
type: docs
url: "/net/aspose.pdf.ai/ichatcopilot/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/ichatcopilot/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:50:26+00:00"
---
## IChatCopilot interface {#ichatcopilot-interface}

Represents a chat copilot for interacting with documents via AI models.

```csharp
public interface IChatCopilot : IAICopilot
```

## Methods {#methods}

| Name | Description |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Asynchronously deletes the context. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List<string>, CancellationToken?) | Asynchronously gets a response for the given list of messages. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Asynchronously gets a response for the given message. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Asynchronously saves the context to a JSON file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List<string>, string, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a PDF file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Asynchronously saves the response for the given message to a PDF file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List<string>, string, SaveFormat, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a file with specified format. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Asynchronously saves the response for the given message to a file with specified format. |

### See Also {#see-also}

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)
