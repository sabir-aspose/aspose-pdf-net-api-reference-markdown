---
title: "PdfXmpMetadata.Item"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata property. Gets or sets value by key"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/item/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/item/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:22+00:00"
---
## PdfXmpMetadata indexer (1 of 2) {#pdfxmpmetadata-indexer-1-of-2}

Gets or sets value by key.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parameter | Description |
| --- | --- |
| key | The key name to get/set. |

### Return Value {#return-value}

Object by key

## Examples {#examples}

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### See Also {#see-also}

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2) {#pdfxmpmetadata-indexer-2-of-2}

Gets value of XMP metadata by key.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parameter | Description |
| --- | --- |
| key | Key of the value. |

### Return Value {#return-value-1}

Value from XMP metadata.

## Examples {#examples-1}

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### See Also {#see-also-1}

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
