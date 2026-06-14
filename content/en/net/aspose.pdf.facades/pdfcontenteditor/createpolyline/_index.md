---
title: "PdfContentEditor.CreatePolyLine"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates polyline annotation"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:02+00:00"
---
## PdfContentEditor.CreatePolyLine method {#pdfcontenteditorcreatepolyline-method}

Creates polyline annotation.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| lineInfo | LineInfo | The instance of LineInfo class. |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | String | The contents of the annotation. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
