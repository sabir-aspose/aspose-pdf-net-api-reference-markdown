---
title: "PdfViewer.Resolution"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer property. Gets or sets resolution during viewing and printing. The higher resolution the slower speed. The default value is 150"
type: docs
url: "/net/aspose.pdf.facades/pdfviewer/resolution/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfviewer/resolution/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:07+00:00"
---
## PdfViewer.Resolution property {#pdfviewerresolution-property}

Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150.

```csharp
public int Resolution { get; set; }
```

## Remarks {#remarks}

This property changes the image resolution in page-to-image conversion flows: when the [`PrintAsImage`](../printasimage/) is set to `true`, or when [`DecodePage`](../decodepage/) or [`DecodeAllPages`](../decodeallpages/) method is called. To set a printer resolution for direct printing to a printer, use the [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) property in the [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) class.

### See Also {#see-also}

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
