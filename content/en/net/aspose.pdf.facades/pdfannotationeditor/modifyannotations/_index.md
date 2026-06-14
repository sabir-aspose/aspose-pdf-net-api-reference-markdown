---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties Modified Title Contents Color Subject and Open"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:37+00:00"
---
## PdfAnnotationEditor.ModifyAnnotations method {#pdfannotationeditormodifyannotations-method}

Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parameter | Type | Description |
| --- | --- | --- |
| start | Int32 | The start page number. |
| end | Int32 | The end page number. |
| annotation | Annotation | The annotation object contains new properties. |

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
