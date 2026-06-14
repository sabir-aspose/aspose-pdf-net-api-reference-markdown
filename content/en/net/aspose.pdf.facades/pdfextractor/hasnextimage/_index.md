---
title: "PdfExtractor.HasNextImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Checks if more images are accessible in PDF document. Note ExtractImage must be called before using of this method"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/hasnextimage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/hasnextimage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:56+00:00"
---
## PdfExtractor.HasNextImage method {#pdfextractorhasnextimage-method}

Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method.

```csharp
public bool HasNextImage()
```

### Return Value {#return-value}

Trues if more images are accessible

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
