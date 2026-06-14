---
title: "PdfContentEditor.CreatePopup"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates popup annotation in PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createpopup/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createpopup/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:03+00:00"
---
## PdfContentEditor.CreatePopup method {#pdfcontenteditorcreatepopup-method}

Creates popup annotation in PDF document.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | String | The contents of the annotation. |
| open | Boolean | A flag specifying whether the pop-up annotation should initially be displayed open. |
| page | Int32 | The number of original page where the annotation will be created. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
