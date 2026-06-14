---
title: "PdfFileEditor.Delete"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Deletes pages specified by number array from input file saves as a new Pdf file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/delete/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/delete/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:13+00:00"
---
## Delete(string, int[], string) {#delete_1}

Deletes pages specified by number array from input file, saves as a new Pdf file.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input file path. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputFile | String | Output file path. |

### Return Value {#return-value}

True if operation was succeeded.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Deletes pages specified by number array from input file, saves as a new Pdf file.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input file Stream. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputStream | Stream | Output file stream. |

### Return Value {#return-value-1}

True for success, or false.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
