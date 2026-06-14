---
title: "CompletionCreateRequest.ToolChoice"
second_title: "Aspose.PDF for .NET API Reference"
description: "CompletionCreateRequest property. Gets or sets an object that controls which if any tool is called by the model. none means the model will not call any tool and instead generates a message. auto means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools. Specifying a particular tool via type function function name my_function forces the model to call that tool. none is the default when no tools are present.auto is the default if tools are present"
type: docs
url: "/net/aspose.pdf.ai/completioncreaterequest/toolchoice/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/completioncreaterequest/toolchoice/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:48:40+00:00"
---
## CompletionCreateRequest.ToolChoice property {#completioncreaterequesttoolchoice-property}

Gets or sets an object that controls which (if any) tool is called by the model. none means the model will not call any tool and instead generates a message. auto means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools. Specifying a particular tool via {“type”: “function”, “function”: {“name”: “my_function”}} forces the model to call that tool. none is the default when no tools are present.auto is the default if tools are present.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### See Also {#see-also}

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
