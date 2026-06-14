---
title: "PdfFileEditor.SplitToEnd"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits from location and saves the rear part as a new file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/splittoend/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/splittoend/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:29+00:00"
---
## SplitToEnd(string, int, string) {#splittoend_1}

Splits from location, and saves the rear part as a new file.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source Pdf file. |
| location | Int32 | The splitting position. |
| outputFile | String | Output Pdf file path. |

### Return Value {#return-value}

True for success, or false.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Splits from specified location, and saves the rear part as a new file Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source Pdf file Stream. |
| location | Int32 | The splitting position. |
| outputStream | Stream | Output Pdf file Stream. |

### Return Value {#return-value-1}

True for success, or false.

## Remarks {#remarks}

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
