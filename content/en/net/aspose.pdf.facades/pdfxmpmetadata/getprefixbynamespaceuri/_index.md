---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Gets the prefix by namespace URI"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:19+00:00"
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method {#pdfxmpmetadatagetprefixbynamespaceuri-method}

Gets the prefix by namespace URI.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | String | Namespace URI. |

### Return Value {#return-value}

The prefix value.

## Examples {#examples}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### See Also {#see-also}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
