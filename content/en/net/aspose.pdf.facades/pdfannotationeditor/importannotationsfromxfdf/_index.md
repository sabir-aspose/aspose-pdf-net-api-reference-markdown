---
title: "PdfAnnotationEditor.ImportAnnotationsFromXfdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Imports all annotations from XFDF file"
type: docs
url: "/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:36+00:00"
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Imports all annotations from XFDF file.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | String | The input XFDF file. |

## Examples {#examples}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Imports all annotations from XFDF data stream.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | Stream | The input XFDF data stream. |

## Examples {#examples-1}

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
