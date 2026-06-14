---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Flattens all annotations in the document"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:33+00:00"
---
## FlatteningAnnotations() {#flatteningannotations}

Flattens all annotations in the document.

```csharp
public void FlatteningAnnotations()
```

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### See Also {#see-also}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Flattens all annotations in the document.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Specifies modes of flattening. |

### See Also {#see-also-1}

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Flattens the annotations of the specified types.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| start | Int32 | The start page. |
| end | Int32 | Then end page. |
| annotType | AnnotationType[] | The annotation types should be flattened. |

## Examples {#examples-1}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### See Also {#see-also-2}

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
