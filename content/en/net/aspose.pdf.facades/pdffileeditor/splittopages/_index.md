---
title: "PdfFileEditor.SplitToPages"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits the PDF file into singlepage documents"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/splittopages/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/splittopages/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:30+00:00"
---
## SplitToPages(string) {#splittopages_1}

Splits the PDF file into single-page documents.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input PDF file name. |

### Return Value {#return-value}

Output PDF streams, each stream buffers a single-page PDF document.

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Splits the Pdf file into single-page documents.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Pdf stream. |

### Return Value {#return-value-1}

Array of memory streams which contain pages of the document.

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input file name. |
| fileNameTemplate | String | Template of resultant file name. Must contain %NUM% which is replaced with page number. For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### See Also {#see-also-2}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream of the soruce document. |
| fileNameTemplate | String | Template of resultant file name. Must contain %NUM% which is replaced with page number. For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### See Also {#see-also-3}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
