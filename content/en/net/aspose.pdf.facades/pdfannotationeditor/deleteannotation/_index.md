---
title: "PdfAnnotationEditor.DeleteAnnotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Deletes the annotation with specified annotation name"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:29+00:00"
---
## PdfAnnotationEditor.DeleteAnnotation method {#pdfannotationeditordeleteannotation-method}

Deletes the annotation with specified annotation name.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotName | String | The annotation name |

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
