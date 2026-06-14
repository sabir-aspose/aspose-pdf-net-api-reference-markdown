---
title: "PdfFileStamp.AddHeader"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileStamp method. Adds header to the page"
type: docs
url: "/net/aspose.pdf.facades/pdffilestamp/addheader/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilestamp/addheader/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:56+00:00"
---
## AddHeader(FormattedText, float) {#addheader}

Adds header to the page.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Text for header and properties of the text. |
| topMargin | Single | Margin on the top of page. |

## Examples {#examples}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### See Also {#see-also}

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Adds header to the pages of file.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Formatted text object which contains page text and its properties. |
| topMargin | Single | Margin on the top of the page. |
| leftMargin | Single | Margin on the left of the page. |
| rightMargin | Single | Margin on the right of the page. |

## Examples {#examples-1}

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### See Also {#see-also-1}

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Adds image as header to the pages of the file.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Path to the image file. |
| topMargin | Single | Margin at top of the page. |

## Examples {#examples-2}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### See Also {#see-also-2}

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Adds image as header on the pages.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Path to the image file. |
| topMargin | Single | Margin at top of the page. |
| leftMargin | Single | Margin at left side of the page. |
| rightMargin | Single | Margin at right side of the page. |

## Examples {#examples-3}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### See Also {#see-also-3}

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Adds image as header on the pages.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Stream of the image. |
| topMargin | Single | Margin at top of the page. |

## Examples {#examples-4}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### See Also {#see-also-4}

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Adds image at the top of the page.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream which contains image data. |
| topMargin | Single | Margin at top of the page. |
| leftMargin | Single | Margin at left side of the page. |
| rightMargin | Single | Margin at right side of the page. |

## Examples {#examples-5}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### See Also {#see-also-5}

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
