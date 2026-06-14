---
title: "PdfContentEditor.CreateRubberStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates a rubber stamp annotation"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:04+00:00"
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Creates a rubber stamp annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| icon | String | An icon is to be used in displaying the annotation. Default value: ‘Draft’. |
| annotContents | String | The contents of the annotation. |
| color | Color | The color of the annotation. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Creates a rubber stamp annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | String | The contents of the annotation. |
| color | Color | The colour of the annotation. |
| appearanceFile | String | The path of appearance file. |

## Examples {#examples-1}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Creates a rubber stamp annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | String | The contents of the annotation. |
| color | Color | The colour of the annotation. |
| appearanceStream | Stream | The stream of appearance file. |

## Examples {#examples-2}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### See Also {#see-also-2}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
