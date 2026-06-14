---
title: "PdfFileEditor.LastException"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor property. Gets last occured exception. May be used to check the reason of failure"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/lastexception/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/lastexception/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:18+00:00"
---
## PdfFileEditor.LastException property {#pdffileeditorlastexception-property}

Gets last occured exception. May be used to check the reason of failure.

```csharp
public Exception LastException { get; }
```

## Examples {#examples}

```csharp
PdfFileEditor pfe = new PdfFileEditor();
if (!pfe.TryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
{
   Console.WriteLine("Error occured:");
   if (pfe.LastException != null)
   {
       Console.WriteLine(pfe.LastException.Message);
       if (pfe.LastException.InnerException != null)
           Console.WriteLine(pfe.LastException.InnerException.Message);
   }
}
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
