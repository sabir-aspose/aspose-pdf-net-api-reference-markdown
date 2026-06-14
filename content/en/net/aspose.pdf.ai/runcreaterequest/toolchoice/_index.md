---
title: "RunCreateRequest.ToolChoice"
second_title: "Aspose.PDF for .NET API Reference"
description: "RunCreateRequest property. Gets or sets which if any tool is called by the model. none means the model will not call any tools and instead generates a message. auto is the default value and means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools before responding to the user. Specifying a particular tool like type file_search or type function function name my_function forces the model to call that tool"
type: docs
url: "/net/aspose.pdf.ai/runcreaterequest/toolchoice/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/runcreaterequest/toolchoice/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:55:46+00:00"
---
## RunCreateRequest.ToolChoice property {#runcreaterequesttoolchoice-property}

Gets or sets which (if any) tool is called by the model. none means the model will not call any tools and instead generates a message. auto is the default value and means the model can pick between generating a message or calling one or more tools. required means the model must call one or more tools before responding to the user. Specifying a particular tool like {“type”: “file_search”} or {“type”: “function”, “function”: {“name”: “my_function”}} forces the model to call that tool.

```csharp
public string ToolChoice { get; set; }
```

### See Also {#see-also}

* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
