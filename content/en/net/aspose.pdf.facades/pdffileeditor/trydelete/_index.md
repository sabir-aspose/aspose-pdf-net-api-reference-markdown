---
title: "PdfFileEditor.TryDelete"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Deletes pages specified by number array from input file saves as a new Pdf file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/trydelete/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/trydelete/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:33+00:00"
---
## TryDelete(string, int[], string) {#trydelete_1}

Deletes pages specified by number array from input file, saves as a new Pdf file.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input file path. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputFile | String | Output file path. |

### Return Value {#return-value}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks}

The TryDelete method is like the Delete method, except the TryDelete method does not throw an exception if the operation fails.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Deletes pages specified by number array from input file, saves as a new Pdf file.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input file Stream. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputStream | Stream | Output file stream. |

### Return Value {#return-value-1}

True for success, or false.

## Remarks {#remarks-1}

The TryDelete method is like the Delete method, except the TryDelete method does not throw an exception if the operation fails.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
