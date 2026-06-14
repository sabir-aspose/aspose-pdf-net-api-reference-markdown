---
title: "PdfExtractor.EndPage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor property. Gets or sets end page in the page range where extracting operation will be performed"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/endpage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/endpage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:46+00:00"
---
## PdfExtractor.EndPage property {#pdfextractorendpage-property}

Gets or sets end page in the page range where extracting operation will be performed.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
