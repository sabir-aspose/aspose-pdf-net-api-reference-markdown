---
title: "PdfContentEditor.ReplaceImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Replaces the specified image on the specified page of PDF document with another image"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:24+00:00"
---
## PdfContentEditor.ReplaceImage method {#pdfcontenteditorreplaceimage-method}

Replaces the specified image on the specified page of PDF document with another image.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | The number of page on which the image is replaced. |
| index | Int32 | The index of the image object must be replaced. |
| imageFile | String | The image file will be used for replacing. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
