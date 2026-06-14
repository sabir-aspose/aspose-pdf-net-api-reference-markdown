---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Gets the list of annotations of the specified types"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:32+00:00"
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Gets the list of annotations of the specified types.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| start | Int32 | Start page from which the annotations will be selected. |
| end | Int32 | End page to which the annotations will be selected. |
| annotTypes | String[] | The array of needed annotation types. |

### Return Value {#return-value}

Annotations list.

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### See Also {#see-also}

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Gets the list of annotations of the specified types.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| start | Int32 | Start page from which the annotations will be selected. |
| end | Int32 | End page to which the annotations will be selected. |
| annotTypes | AnnotationType[] | The array of needed annotation types. |

### Return Value {#return-value-1}

Annotations list.

## Examples {#examples-1}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### See Also {#see-also-1}

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
