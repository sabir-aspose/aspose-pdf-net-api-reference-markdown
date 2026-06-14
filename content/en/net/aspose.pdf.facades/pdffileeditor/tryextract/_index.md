---
title: "PdfFileEditor.TryExtract"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Extracts pages from input filesaves as a new Pdf file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/tryextract/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/tryextract/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:34+00:00"
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extracts pages from input file,saves as a new Pdf file.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input Pdf file path. |
| startPage | Int32 | Start page number. |
| endPage | Int32 | End page number. |
| outputFile | String | Output Pdf file path. |

### Return Value {#return-value}

True for success, or false.

## Remarks {#remarks}

The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extracts pages specified by number array, saves as a new PDF file.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input file path. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputFile | String | Output file path. |

### Return Value {#return-value-1}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-1}

The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extracts pages specified by number array, saves as a new Pdf file.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input file Stream. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputStream | Stream | Output file stream. |

### Return Value {#return-value-2}

True for success, or false.

## Remarks {#remarks-2}

The TryExtract method is like the Extract method, except the TryExtract method does not throw an exception if the operation fails.

## Examples {#examples-2}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### See Also {#see-also-2}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
