---
title: "Class DjvuLoadOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.DjvuLoadOptions class. Class describes DJVU load options"
type: docs
url: "/net/aspose.pdf/djvuloadoptions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/djvuloadoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:53:42+00:00"
---
## DjvuLoadOptions class {#djvuloadoptions-class}

Class describes DJVU load options.

```csharp
public class DjvuLoadOptions : LoadOptions
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [DjvuLoadOptions](djvuloadoptions/)() | The default constructor. |

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
