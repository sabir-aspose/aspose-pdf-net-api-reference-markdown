---
title: "PdfContentEditor.CreateMarkup"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates markup annotation it PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:59+00:00"
---
## PdfContentEditor.CreateMarkup method {#pdfcontenteditorcreatemarkup-method}

Creates markup annotation it PDF document.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle defining the location of the annotation on the page. |
| contents | String | The contents of the annotation. |
| type | Int32 | The type of markup annotation. Can be 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| page | Int32 | The number of original page where the annotation will be created. |
| clr | Color | The color of markup. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
