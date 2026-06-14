---
title: "PdfFileStamp.AddStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileStamp method. Adds stamp to the file"
type: docs
url: "/net/aspose.pdf.facades/pdffilestamp/addstamp/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilestamp/addstamp/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:58+00:00"
---
## PdfFileStamp.AddStamp method {#pdffilestampaddstamp-method}

Adds stamp to the file.

```csharp
public void AddStamp(Stamp stamp)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stamp | Stamp | Stamp object which. |

## Examples {#examples}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also {#see-also}

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
