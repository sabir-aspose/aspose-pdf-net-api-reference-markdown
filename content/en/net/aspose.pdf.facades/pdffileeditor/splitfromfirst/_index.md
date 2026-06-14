---
title: "PdfFileEditor.SplitFromFirst"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Splits Pdf file from first page to specified locationand saves the front part as a new file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:28+00:00"
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Splits Pdf file from first page to specified location,and saves the front part as a new file.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source Pdf file. |
| location | Int32 | The splitting point. |
| outputFile | String | Output Pdf file. |

### Return Value {#return-value}

True for success, or false.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Splits from start to specified location,and saves the front part in output Stream.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source Pdf file Stream. |
| location | Int32 | The splitting point. |
| outputStream | Stream | Output file Stream. |

### Return Value {#return-value-1}

True for success, or false.

## Remarks {#remarks}

The streams are NOT closed after this operation.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
