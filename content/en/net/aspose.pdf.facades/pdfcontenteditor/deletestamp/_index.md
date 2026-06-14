---
title: "PdfContentEditor.DeleteStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Deletes multiple stamps on the specified page by stamp indexes"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:10+00:00"
---
## PdfContentEditor.DeleteStamp method {#pdfcontenteditordeletestamp-method}

Deletes multiple stamps on the specified page by stamp indexes.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Page number where stamp will be deleted. |
| index | Int32[] | Stamp indexes. |

## Examples {#examples}

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
