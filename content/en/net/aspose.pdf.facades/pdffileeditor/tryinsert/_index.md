---
title: "PdfFileEditor.TryInsert"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Inserts pages from an other file into the input Pdf file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/tryinsert/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/tryinsert/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:34+00:00"
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Inserts pages from an other file into the input Pdf file.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input Pdf file. |
| insertLocation | Int32 | Insert position in input file. |
| portFile | String | Pages from the Pdf file. |
| pageNumber | Int32[] | The page number of the ported in portFile. |
| outputFile | String | Output Pdf file. |

### Return Value {#return-value}

True for success, or false.

## Remarks {#remarks}

The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Inserts pages from an other file into the input Pdf file.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Stream of Pdf file. |
| insertLocation | Int32 | Insert position in input file. |
| portStream | Stream | Stream of Pdf file for pages. |
| pageNumber | Int32[] | The page number of the ported in portFile. |
| outputStream | Stream | Output Stream. |

### Return Value {#return-value-1}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-1}

The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
