---
title: "PdfExtractor.ExtractTextMode"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor property. Sets the mode for extract texts result"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/extracttextmode/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/extracttextmode/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:50+00:00"
---
## PdfExtractor.ExtractTextMode property {#pdfextractorextracttextmode-property}

Sets the mode for extract text’s result.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value {#property-value}

0 is pure text mode and 1 is raw ordering mode. Default is 0.

## Examples {#examples}

The example demonstrates the `ExtractTextMode` property usage in text extraction scenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
