---
title: "PdfExtractor.GetNextImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Retrieves next image from PDF document. Note ExtractImage must be called before using of this method"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/getnextimage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/getnextimage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:53+00:00"
---
## GetNextImage(string) {#getnextimage_2}

Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | File where image will be stored |

### Return Value {#return-value}

True is image is successfully extracted

## Examples {#examples}

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Retrieves next image from PDF document with given image format. Note: ExtractImage must be called before using of this method.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | File where image will be stored |
| format | ImageFormat | The format of the image. |

### Return Value {#return-value-1}

True is image is successfully extracted

### See Also {#see-also-1}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Retrieve next image from PDF file and stores it into stream with given image format.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where image data will be saved |
| format | ImageFormat | The format of the image. |

### Return Value {#return-value-2}

True in case the image is successfully extracted.

### See Also {#see-also-2}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Retrieve next image from PDF file and stores it into stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where image data will be saved |

### Return Value {#return-value-3}

True in case the image is successfully extracted.

### See Also {#see-also-3}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
