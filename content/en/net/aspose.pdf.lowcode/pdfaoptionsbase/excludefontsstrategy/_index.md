---
title: "PdfAOptionsBase.ExcludeFontsStrategy"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAOptionsBase property. Gets or sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process"
type: docs
url: "/net/aspose.pdf.lowcode/pdfaoptionsbase/excludefontsstrategy/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/pdfaoptionsbase/excludefontsstrategy/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:31:04+00:00"
---
## PdfAOptionsBase.ExcludeFontsStrategy property {#pdfaoptionsbaseexcludefontsstrategy-property}

Gets or sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value {#property-value}

The strategy for removing fonts. This can be one of the values from the [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) enumeration. The default is the combination of SubsetFonts and RemoveDuplicatedFonts.

## Remarks {#remarks}

This property allows you to control how fonts are handled during the conversion process. You can choose to remove duplicated fonts, remove similar fonts with different widths, or subset fonts.

### See Also {#see-also}

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.LowCode](../../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../../)
