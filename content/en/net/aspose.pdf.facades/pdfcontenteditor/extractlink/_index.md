---
title: "PdfContentEditor.ExtractLink"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Extracts the collection of Link instances contained in PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/extractlink/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/extractlink/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:18+00:00"
---
## PdfContentEditor.ExtractLink method {#pdfcontenteditorextractlink-method}

Extracts the collection of Link instances contained in PDF document.

```csharp
public IList<Annotation> ExtractLink()
```

### Return Value {#return-value}

The collection of Link objects

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### See Also {#see-also}

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
