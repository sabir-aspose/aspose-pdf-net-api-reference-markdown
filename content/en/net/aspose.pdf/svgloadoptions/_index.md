---
title: "Class SvgLoadOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.SvgLoadOptions class. Represents options for loading/importing SVG file into pdf document"
type: docs
url: "/net/aspose.pdf/svgloadoptions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/svgloadoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:08:55+00:00"
---
## SvgLoadOptions class {#svgloadoptions-class}

Represents options for loading/importing SVG file into pdf document.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | The default constructor. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Adust pdf page size to svg size |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Gets or sets page info that should be applied during loading of document. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

## Fields {#fields}

| Name | Description |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine |

### See Also {#see-also}

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
