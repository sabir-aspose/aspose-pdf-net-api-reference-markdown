---
title: "PdfConverter.BindPdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfConverter method. Binds a Pdf file for converting"
type: docs
url: "/net/aspose.pdf.facades/pdfconverter/bindpdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfconverter/bindpdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:30+00:00"
---
## BindPdf(string) {#bindpdf_2}

Binds a Pdf file for converting.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | The pdf file. |

### See Also {#see-also}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Binds a Pdf Stream for convert.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf Stream. |

### See Also {#see-also-1}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Document) {#bindpdf}

Binds a PDF document to the [`PdfConverter`](../) instance for further processing.

```csharp
public override void BindPdf(Document srcDoc)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | Document | The [`Document`](../../../aspose.pdf/document/) object representing the source PDF to be bound. |

## Remarks {#remarks}

This method initializes the [`PdfConverter`](../) with the specified PDF document. It also processes dynamic XFA forms within the document, if present.

### See Also {#see-also-2}

* class [Document](../../../aspose.pdf/document/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
