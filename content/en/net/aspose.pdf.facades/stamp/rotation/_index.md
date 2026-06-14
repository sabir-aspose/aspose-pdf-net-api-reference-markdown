---
title: "Stamp.Rotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Stamp property. Gets or sets rotation of the stamp in degrees"
type: docs
url: "/net/aspose.pdf.facades/stamp/rotation/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/stamp/rotation/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:47+00:00"
---
## Stamp.Rotation property {#stamprotation-property}

Gets or sets rotation of the stamp in degrees.

```csharp
public float Rotation { get; set; }
```

## Examples {#examples}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also {#see-also}

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
