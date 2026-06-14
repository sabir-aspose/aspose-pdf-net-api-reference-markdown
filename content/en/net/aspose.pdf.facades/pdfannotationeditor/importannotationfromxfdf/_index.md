---
title: "PdfAnnotationEditor.ImportAnnotationFromXfdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Imports the specified annotations from XFDF file"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:34+00:00"
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

Imports the specified annotations from XFDF file.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | String | The input XFDF file. |
| annotType | AnnotationType[] | The annotations array to be imported. |

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Imports the specified annotations from XFDF data stream.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | Stream | The input XFDF data stream. |
| annotType | AnnotationType[] | The array of annotation types to be imported. |

## Examples {#examples-1}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
