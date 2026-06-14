---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Get the XmpMetadata of the input pdf in a xml format"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:20+00:00"
---
## GetXmpMetadata() {#getxmpmetadata}

Get the XmpMetadata of the input pdf in a xml format.

```csharp
public byte[] GetXmpMetadata()
```

### Return Value {#return-value}

The bytes of the XmpMetadata.

## Examples {#examples}

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### See Also {#see-also}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Get a part of the XmpMetadata of the input pdf according to a meta name.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Metadata name. |

### Return Value {#return-value-1}

Bytes of metadata.

## Examples {#examples-1}

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### See Also {#see-also-1}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
