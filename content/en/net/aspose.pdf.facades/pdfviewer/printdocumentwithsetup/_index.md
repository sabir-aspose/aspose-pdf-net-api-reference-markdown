---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfViewer method. Prints the Pdf document with a setup dialog. Choose a printer using the dialog"
type: docs
url: "/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:03+00:00"
---
## PdfViewer.PrintDocumentWithSetup method {#pdfviewerprintdocumentwithsetup-method}

Prints the Pdf document with a setup dialog. Choose a printer using the dialog.

```csharp
public void PrintDocumentWithSetup()
```

## Examples {#examples}

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup();
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True          'print the file with adjusted size
iewer.AutoRotate = True          'print the file with adjusted rotation
iewer.PrintPageDialog = False    'do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup()
iewer.Close()
```

### See Also {#see-also}

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
