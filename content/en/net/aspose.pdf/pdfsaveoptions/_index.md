---
title: "Class PdfSaveOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.PdfSaveOptions class. Save options for export to Pdf format"
type: docs
url: "/net/aspose.pdf/pdfsaveoptions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/pdfsaveoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:06:42+00:00"
---
## PdfSaveOptions class {#pdfsaveoptions-class}

Save options for export to Pdf format

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | The default constructor. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with [`DefaultFontName`](./defaultfontname/) is found on device) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Path for temporary files. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

### See Also {#see-also}

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
