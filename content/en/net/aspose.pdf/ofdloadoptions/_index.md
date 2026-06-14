---
title: "Class OfdLoadOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.OfdLoadOptions class. Load options for OFD format"
type: docs
url: "/net/aspose.pdf/ofdloadoptions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/ofdloadoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:01:52+00:00"
---
## OfdLoadOptions class {#ofdloadoptions-class}

Load options for OFD format.

```csharp
public class OfdLoadOptions : LoadOptions
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | The default constructor. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

### See Also {#see-also}

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
