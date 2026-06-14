---
title: "PdfFileEditor.TryConcatenate"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Concatenates two files"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:32+00:00"
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Concatenates two files.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | First file to concatenate. |
| secInputFile | String | Second file to concatenate. |
| outputFile | String | Output file. |

### Return Value {#return-value}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks}

The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails.

## Examples {#examples}

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatenates documents.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| src | Document[] | Array of source documents. |
| dest | Document | Destination document. |

### Return Value {#return-value-1}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-1}

The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails.

### See Also {#see-also-1}

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Concatenates files into one file.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Array of files to concatenate. |
| outputFile | String | Name of output file. |

### Return Value {#return-value-2}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-2}

The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### See Also {#see-also-2}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatenates files

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | Array of streams to be concatenated. |
| outputStream | Stream | Stream where result file will be stored. |

### Return Value {#return-value-3}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-3}

The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails.

## Examples {#examples-2}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### See Also {#see-also-3}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1’, p2’, p3’. Merging the two Pdf document will produce the result document with pages:p1, p1’, p2, p2’, p3, p3’, p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | First file. |
| secInputFile | String | Second file. |
| blankPageFile | String | PDF file with blank page. |
| outputFile | String | Result file. |

### Return Value {#return-value-4}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-4}

The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails.

## Examples {#examples-3}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### See Also {#see-also-4}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1’, p2’, p3’. Merging the two Pdf document will produce the result document with pages:p1, p1’, p2, p2’, p3, p3’, p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | The first Pdf Stream. |
| secInputStream | Stream | The second Pdf Stream. |
| blankPageStream | Stream | The Pdf Stream with blank page. |
| outputStream | Stream | Output Pdf Stream. |

### Return Value {#return-value-5}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-5}

The TryConcatenate method is like the Concatenate method, except the TryConcatenate method does not throw an exception if the operation fails.

## Examples {#examples-4}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### See Also {#see-also-5}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
