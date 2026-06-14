---
title: "PdfContentEditor.CreateText"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates text annotation in PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createtext/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createtext/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:06+00:00"
---
## PdfContentEditor.CreateText method {#pdfcontenteditorcreatetext-method}

Creates text annotation in PDF document

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| title | String | The title of the annotation. |
| contents | String | The contents of the annotation. |
| open | Boolean | A flag specifying whether the annotation should initially be displayed open. |
| icon | String | The name of an icon will be used in displaying the annotation. This value can be: “Comment”, “Key”, “Note”, “Help”, “NewParagraph”, “Paragraph”, “Insert” |
| page | Int32 | The number of original page where the text annotation will be created. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
