---
title: "PdfExtractor.GetAttachNames"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Returns list of attachments in PDF file. Note ExtractAttachments must be called before using this method"
type: docs
url: "/net/aspose.pdf.facades/pdfextractor/getattachnames/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfextractor/getattachnames/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:52+00:00"
---
## PdfExtractor.GetAttachNames method {#pdfextractorgetattachnames-method}

Returns list of attachments in PDF file. Note: ExtractAttachments must be called before using this method.

```csharp
public IList<string> GetAttachNames()
```

### Return Value {#return-value}

List of attachments

## Examples {#examples}

Example demonstrates how to extract attachment names form PDF file.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### See Also {#see-also}

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
