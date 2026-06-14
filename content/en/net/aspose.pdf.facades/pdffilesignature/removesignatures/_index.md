---
title: "PdfFileSignature.RemoveSignatures"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSignature method. Removes all signatures"
type: docs
url: "/net/aspose.pdf.facades/pdffilesignature/removesignatures/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesignature/removesignatures/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:48+00:00"
---
## PdfFileSignature.RemoveSignatures method {#pdffilesignatureremovesignatures-method}

Removes all signatures.

```csharp
public void RemoveSignatures()
```

## Examples {#examples}

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
var pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
pdfSign.RemoveSignatures();
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
pdfSign.RemoveSignatures()
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### See Also {#see-also}

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
