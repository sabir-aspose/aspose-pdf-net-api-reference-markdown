---
title: "PdfConverter.SaveAsTIFFClassF"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfConverter method. Converts each pages of a pdf document to images and save images to a single TIFF ClassF file"
type: docs
url: "/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:43+00:00"
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |

## Examples {#examples}

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### See Also {#see-also}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The stream to save the TIFF image. |
| pageSize | PageSize | The page size of the image. |

### See Also {#see-also-1}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |

### See Also {#see-also-2}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| pageSize | PageSize | The page size of the image. |

### See Also {#see-also-3}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The stream to save the TIFF image. |

## Examples {#examples-1}

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### See Also {#see-also-4}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |

### See Also {#see-also-5}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
