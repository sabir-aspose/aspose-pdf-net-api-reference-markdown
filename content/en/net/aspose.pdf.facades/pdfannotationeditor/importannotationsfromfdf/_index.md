---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Imports all annotations from FDF file"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:35+00:00"
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method {#pdfannotationeditorimportannotationsfromfdf-method}

Imports all annotations from FDF file.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fdfFile | String | The input FDF file. |

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
