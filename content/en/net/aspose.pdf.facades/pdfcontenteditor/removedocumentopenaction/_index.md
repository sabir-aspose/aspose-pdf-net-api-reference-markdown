---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit GoTo action on startup"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:23+00:00"
---
## PdfContentEditor.RemoveDocumentOpenAction method {#pdfcontenteditorremovedocumentopenaction-method}

Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit ‘GoTo’ action on startup.

```csharp
public void RemoveDocumentOpenAction()
```

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
