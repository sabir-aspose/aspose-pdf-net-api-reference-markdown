---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Gets namespace URI by prefix"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:18+00:00"
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method {#pdfxmpmetadatagetnamespaceuribyprefix-method}

Gets namespace URI by prefix.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix. |

### Return Value {#return-value}

Namespace URI.

## Examples {#examples}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### See Also {#see-also}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
