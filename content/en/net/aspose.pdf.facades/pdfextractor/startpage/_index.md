---
title: "PdfExtractor.StartPage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor property. Gets or sets start page in the page range where extracting operation will be performed"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/startpage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/startpage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:00+00:00"
---
## PdfExtractor.StartPage property {#pdfextractorstartpage-property}

Gets or sets start page in the page range where extracting operation will be performed.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
