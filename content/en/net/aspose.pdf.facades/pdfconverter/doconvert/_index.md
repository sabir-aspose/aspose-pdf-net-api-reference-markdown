---
title: "PdfConverter.DoConvert"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfConverter method. Do some initial works for converting a pdf document to images"
type: docs
url: "/net/aspose.pdf.facades/pdfconverter/doconvert/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfconverter/doconvert/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:33+00:00"
---
## PdfConverter.DoConvert method {#pdfconverterdoconvert-method}

Do some initial works for converting a pdf document to images.

```csharp
public void DoConvert()
```

## Examples {#examples}

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix)
	imageCount = imageCount + 1
End While
```

### See Also {#see-also}

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
