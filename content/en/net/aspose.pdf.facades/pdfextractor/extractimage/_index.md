---
title: "PdfExtractor.ExtractImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Extract images from PDF file"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/extractimage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/extractimage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:48+00:00"
---
## PdfExtractor.ExtractImage method {#pdfextractorextractimage-method}

Extract images from PDF file.

```csharp
public void ExtractImage()
```

## Examples {#examples}

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
