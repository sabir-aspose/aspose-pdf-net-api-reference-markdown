---
title: "PdfExtractor.BindPdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Bind input PDF file"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/bindpdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/bindpdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:46+00:00"
---
## BindPdf(string) {#bindpdf_2}

Bind input PDF file.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | PDF file to bind |

## Examples {#examples}

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Binds PDF document from stream.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream containing PDF document data |

## Examples {#examples-1}

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### See Also {#see-also-1}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
