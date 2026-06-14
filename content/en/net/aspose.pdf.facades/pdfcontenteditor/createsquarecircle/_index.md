---
title: "PdfContentEditor.CreateSquareCircle"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates squarecircle annotation"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:05+00:00"
---
## PdfContentEditor.CreateSquareCircle method {#pdfcontenteditorcreatesquarecircle-method}

Creates square-circle annotation.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | String | The contents of the annotation. |
| clr | Color | The colour of square or circle. |
| square | Boolean | True (square), false (sircle). |
| page | Int32 | The number of original page where the annotation will be created. |
| borderWidth | Int32 | The border width of square or circle. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
