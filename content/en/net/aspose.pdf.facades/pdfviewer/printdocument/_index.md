---
title: "PdfViewer.PrintDocument"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer method. Prints the Pdf document using default printer"
type: docs
url: "/net/aspose.pdf.facades/pdfviewer/printdocument/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfviewer/printdocument/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:00+00:00"
---
## PdfViewer.PrintDocument method {#pdfviewerprintdocument-method}

Prints the Pdf document using default printer.

```csharp
public void PrintDocument()
```

## Examples {#examples}

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;         'print the file with adjusted size
iewer.AutoRotate = true;         'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile()
```

### See Also {#see-also}

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
