---
title: "Stamp.Pages"
second_title: "Aspose.PDF for .NET API Reference"
description: "Stamp property. Gets or sets array with numbers of pages which will be affected by stamp. If Pages null all pages of the document are affected"
type: docs
url: "/net/aspose.pdf.facades/stamp/pages/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/stamp/pages/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:45+00:00"
---
## Stamp.Pages property {#stamppages-property}

Gets or sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected.

```csharp
public int[] Pages { get; set; }
```

## Examples {#examples}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also {#see-also}

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
