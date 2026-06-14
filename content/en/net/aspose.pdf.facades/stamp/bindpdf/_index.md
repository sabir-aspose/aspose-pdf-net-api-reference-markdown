---
title: "Stamp.BindPdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "Stamp method. Sets PDF file and number of page which will be used as stamp"
type: docs
url: "/net/aspose.pdf.facades/stamp/bindpdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/stamp/bindpdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:41+00:00"
---
## BindPdf(string, int) {#bindpdf_1}

Sets PDF file and number of page which will be used as stamp.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfFile | String | Path to PDF file. |
| pageNumber | Int32 | Number of page in PDF file |

## Examples {#examples}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also {#see-also}

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Sets PDF file and number of page which will be used as stamp.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | Stream | Stream which contains PDF document. |
| pageNumber | Int32 | Page index of the document whihc will be used as stamp. |

## Examples {#examples-1}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also {#see-also-1}

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
