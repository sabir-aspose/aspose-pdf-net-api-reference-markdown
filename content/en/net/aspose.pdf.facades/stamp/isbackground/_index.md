---
title: "Stamp.IsBackground"
second_title: "Aspose.PDF for .NET API Reference"
description: "Stamp property. Gets or sets background status. If true stamp will be placed as background of the spamped page. By default is set to false"
type: docs
url: "/net/aspose.pdf.facades/stamp/isbackground/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/stamp/isbackground/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:43+00:00"
---
## Stamp.IsBackground property {#stampisbackground-property}

Gets or sets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

```csharp
public bool IsBackground { get; set; }
```

## Examples {#examples}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also {#see-also}

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
