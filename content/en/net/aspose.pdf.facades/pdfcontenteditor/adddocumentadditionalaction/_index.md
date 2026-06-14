---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Adds additional action for document event"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:47+00:00"
---
## PdfContentEditor.AddDocumentAdditionalAction method {#pdfcontenteditoradddocumentadditionalaction-method}

Adds additional action for document event.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parameter | Type | Description |
| --- | --- | --- |
| eventType | String | The document event types. |
| code | String | The code of JavaScript. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
