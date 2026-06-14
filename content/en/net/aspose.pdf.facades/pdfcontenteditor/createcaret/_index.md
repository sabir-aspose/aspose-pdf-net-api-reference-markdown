---
title: "PdfContentEditor.CreateCaret"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates caret annotation"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createcaret/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createcaret/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:53+00:00"
---
## PdfContentEditor.CreateCaret method {#pdfcontenteditorcreatecaret-method}

Creates caret annotation.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| caretRect | Rectangle | The actual boundaries of the underlying caret. |
| symbol | String | A symbol will be associated with the caret. Value can be: “P” (Paragraph), “None”. |
| annotContents | String | The contents of the annotation. |
| color | Color | The color of the annotation. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
