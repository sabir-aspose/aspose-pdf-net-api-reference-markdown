---
title: "PdfContentEditor.CreateFreeText"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates free text annotation in PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:56+00:00"
---
## PdfContentEditor.CreateFreeText method {#pdfcontenteditorcreatefreetext-method}

Creates free text annotation in PDF document

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | String | The contents of the annotation. |
| page | Int32 | The number of original page where the text annotation will be created. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
