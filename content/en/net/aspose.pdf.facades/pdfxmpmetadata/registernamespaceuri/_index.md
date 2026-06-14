---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Registers the namespace URI"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:25+00:00"
---
## PdfXmpMetadata.RegisterNamespaceURI method {#pdfxmpmetadataregisternamespaceuri-method}

Registers the namespace URI.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix. |
| namespaceURI | String | The namespace URI. |

## Examples {#examples}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### See Also {#see-also}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
