---
title: "PdfContentEditor.CreateLocalLink"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates a local link in PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:58+00:00"
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

Creates a local link in PDF document.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| desPage | Int32 | The destination page. |
| originalPage | Int32 | The number of original page where rectangle bound with local link will be created. |
| clr | Color | The colour of rectangle for active click. |
| actionName | Enum[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

Creates a local link in PDF document.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| desPage | Int32 | The destination page. |
| originalPage | Int32 | The number of original page where rectangle bound with local link will be created. |
| clr | Color | The colour of rectangle for active click. |

## Examples {#examples-1}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

Creates a local link in PDF document.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| desPage | Int32 | The destination page. |
| originalPage | Int32 | The number of original page where rectangle bound with local link will be created. |

## Examples {#examples-2}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### See Also {#see-also-2}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
