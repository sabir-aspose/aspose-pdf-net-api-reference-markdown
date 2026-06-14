---
title: "PdfExtractor.HasNextPageText"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Indicates that whether can get more texts or not"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:57+00:00"
---
## PdfExtractor.HasNextPageText method {#pdfextractorhasnextpagetext-method}

Indicates that whether can get more texts or not.

```csharp
public bool HasNextPageText()
```

### Return Value {#return-value}

Can get more texts or not, true is can, or false.

## Examples {#examples}

The example demonstrates the `HasNextPageText` property usage in text extraction scenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
