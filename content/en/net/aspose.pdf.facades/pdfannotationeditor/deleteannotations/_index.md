---
title: "PdfAnnotationEditor.DeleteAnnotations"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Deletes all annotations in the document"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:30+00:00"
---
## DeleteAnnotations() {#deleteannotations}

Deletes all annotations in the document.

```csharp
public void DeleteAnnotations()
```

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Deletes all annotations of the specified type in the document.

```csharp
public void DeleteAnnotations(string annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotType | String | The type of annotation will be deleted. |

## Examples {#examples-1}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
