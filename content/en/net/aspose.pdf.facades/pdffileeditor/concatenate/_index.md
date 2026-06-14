---
title: "PdfFileEditor.Concatenate"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Concatenates files into one file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/concatenate/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/concatenate/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:07+00:00"
---
## Concatenate(string[], string) {#concatenate_6}

Concatenates files into one file.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Array of files to concatenate. |
| outputFile | String | Name of output file. |

### Return Value {#return-value}

True if operation was succeeded.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Concatenates files

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | Array of streams to be concatenated. |
| outputStream | Stream | Stream where result file will be stored. |

### Return Value {#return-value-1}

True if operation was succeeded.

## Examples {#examples-1}

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1’, p2’, p3’. Merging the two Pdf document will produce the result document with pages:p1, p1’, p2, p2’, p3, p3’, p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | First file. |
| secInputFile | String | Second file. |
| blankPageFile | String | PDF file with blank page. |
| outputFile | String | Result file. |

### Return Value {#return-value-2}

True if operation was succeeded.

## Examples {#examples-2}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### See Also {#see-also-2}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1’, p2’, p3’. Merging the two Pdf document will produce the result document with pages:p1, p1’, p2, p2’, p3, p3’, p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | The first Pdf Stream. |
| secInputStream | Stream | The second Pdf Stream. |
| blankPageStream | Stream | The Pdf Stream with blank page. |
| outputStream | Stream | Output Pdf Stream. |

### Return Value {#return-value-3}

True if operation was succeeded.

## Examples {#examples-3}

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### See Also {#see-also-3}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string) {#concatenate_4}

Concatenates two files.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | First file to concatenate. |
| secInputFile | String | Second file to concatenate. |
| outputFile | String | Output file. |

### Return Value {#return-value-4}

True if operation was succeeded.

## Examples {#examples-4}

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### See Also {#see-also-4}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Concatenates two files.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | Stream of first file. |
| secInputStream | Stream | Stream of second file. |
| outputStream | Stream | Stream where result file will be stored. |

### Return Value {#return-value-5}

True if operation was succeeded.

True if operation was succeeded.

## Examples {#examples-5}

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### See Also {#see-also-5}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Concatenates documents.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| src | Document[] | Array of source documents. |
| dest | Document | Destination document. |

### Return Value {#return-value-6}

True if concatenation is successful.

### See Also {#see-also-6}

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
