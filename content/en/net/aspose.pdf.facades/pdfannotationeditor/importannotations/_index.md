---
title: "PdfAnnotationEditor.ImportAnnotations"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Imports the specified annotations into document from array of another PDF documents"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/importannotations/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/importannotations/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:34+00:00"
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Imports the specified annotations into document from array of another PDF documents.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | String[] | The array of paths of PDF documents that contain source annotations. |
| annotType | AnnotationType[] | The array of annotation types to be imported. |

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Imports annotations into document from array of another PDF documents.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | String[] | The array of paths of PDF documents that contain source annotations. |

## Examples {#examples-1}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Imports the specified annotations into document from array of another PDF document streams.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | The array of streams of PDF documents that contain source annotations. |
| annotType | AnnotationType[] | The annotation types to be imported. |

## Examples {#examples-2}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
stream[0]= File.OpenRead("with_annots1.pdf");
stream[1]= File.OpenRead("with_annots2.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(streams, annotTypes);
editor.Save("example_out.pdf");
stream[0].Close();
stream[1].Close();
```

### See Also {#see-also-2}

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Imports annotations into document from array of another PDF document streams.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | The array of streams of PDF documents that contain source annotations. |

## Examples {#examples-3}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
streams[0]= File.OpenRead("with_annots1.pdf");
streams[1]= File.OpenRead("with_annots2.pdf");
editor.ImportAnnotations(streams);
editor.Save("example_out.pdf");
streams[0].Close();
streams[1].Close();
```

### See Also {#see-also-3}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
