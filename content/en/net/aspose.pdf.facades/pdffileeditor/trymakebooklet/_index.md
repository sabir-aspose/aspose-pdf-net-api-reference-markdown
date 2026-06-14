---
title: "PdfFileEditor.TryMakeBooklet"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Makes booklet from the input file to output file"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:35+00:00"
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Makes booklet from the input file to output file.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |

### Return Value {#return-value}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Makes booklet from the InputStream to outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input pdf stream. |
| outputStream | Stream | output pdf stream. |

### Return Value {#return-value-1}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-1}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples-1}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Makes booklet from the inputFile to outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input pdf file path and name. |
| outputFile | String | Output pdf file path and name. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value {#return-value-2}

True if operation is succeeded.

## Remarks {#remarks-2}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples-2}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### See Also {#see-also-2}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Makes booklet from the input stream and save result into output stream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input PDF stream. |
| outputStream | Stream | output pdf stream. |
| pageSize | PageSize | The page size of the output pdf file. |

### Return Value {#return-value-3}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-3}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples-3}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### See Also {#see-also-3}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Makes customized booklet from the firstInputFile to outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | The input file. |
| outputFile | String | Output pdf file path and name. |
| leftPages | Int32[] | The left pages of the booklet. |
| rightPages | Int32[] | The right pages of the booklet. |

### Return Value {#return-value-4}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-4}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples-4}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also {#see-also-4}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Makes customized booklet from the firstInputStream to outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The input stream. |
| outputStream | Stream | output pdf stream. |
| leftPages | Int32[] | The left pages. |
| rightPages | Int32[] | The right pages. |

### Return Value {#return-value-5}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-5}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples-5}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also {#see-also-5}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Makes customized booklet from the firstInputFile to outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | The input file. |
| outputFile | String | Output pdf file path and name. |
| pageSize | PageSize | The page size of the output pdf file. |
| leftPages | Int32[] | The left pages. |
| rightPages | Int32[] | The right pages. |

### Return Value {#return-value-6}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-6}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples-6}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also {#see-also-6}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Makes booklet from the firstInputStream to outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The input stream. |
| outputStream | Stream | output pdf stream. |
| pageSize | PageSize | The page size of the output pdf file. |
| leftPages | Int32[] | The left pages. |
| rightPages | Int32[] | The right pages. |

### Return Value {#return-value-7}

true if operation completed successfully; otherwise, false.

## Remarks {#remarks-7}

The TryMakeBooklet method is like the MakeBooklet method, except the TryMakeBooklet method does not throw an exception if the operation fails.

## Examples {#examples-7}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also {#see-also-7}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
