---
title: "PdfConverter.SaveAsTIFF"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfConverter method. Converts each pages of a pdf document to images and saves images to a single TIFF file"
type: docs
url: "/net/aspose.pdf.facades/pdfconverter/saveastiff/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfconverter/saveastiff/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:42+00:00"
---
## SaveAsTIFF(string) {#saveastiff_10}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file to save the TIFF image. |

## Examples {#examples}

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### See Also {#see-also}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The output file. |
| compressionType | CompressionType | Type of the compression. |

## Examples {#examples-1}

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### See Also {#see-also-1}

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |

### See Also {#see-also-2}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| pageSize | PageSize | The page size of the image. |

### See Also {#see-also-3}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| pageSize | PageSize | The page size of the image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also {#see-also-4}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| compressionType | CompressionType | Type of the compression. |

### See Also {#see-also-5}

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also {#see-also-6}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also {#see-also-7}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |

### See Also {#see-also-8}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The output stream. |
| compressionType | CompressionType | Type of the compression. |

### See Also {#see-also-9}

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| pageSize | PageSize | The page size of the image. |

### See Also {#see-also-10}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| pageSize | PageSize | The page size of the image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also {#see-also-11}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |

### See Also {#see-also-12}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| compressionType | CompressionType | Type of the compression. |

### See Also {#see-also-13}

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also {#see-also-14}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also {#see-also-15}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also {#see-also-16}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also {#see-also-17}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also {#see-also-18}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also {#see-also-19}

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
