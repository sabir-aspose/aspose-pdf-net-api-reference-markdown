---
title: "PdfFileEditor.SplitToBulks"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits the Pdf file into several documents.The documents can be singlepage or multipages"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/splittobulks/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/splittobulks/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:29+00:00"
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input PDF file. |
| numberOfPage | Int32[][] | Array which contains array of double elements, which is start and end pages of document. |

### Return Value {#return-value}

Output PDF streams, each stream buffers a PDF document.

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input PDF stream. |
| numberOfPage | Int32[][] | The start page and the end page of each document. |

### Return Value {#return-value-1}

Output PDF streams, each stream buffers a PDF document.

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
