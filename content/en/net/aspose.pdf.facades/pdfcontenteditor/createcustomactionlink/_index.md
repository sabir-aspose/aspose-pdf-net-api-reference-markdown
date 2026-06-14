---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates a link to custom actions in PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:54+00:00"
---
## PdfContentEditor.CreateCustomActionLink method {#pdfcontenteditorcreatecustomactionlink-method}

Creates a link to custom actions in PDF document.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle for active click. |
| originalPage | Int32 | The number of original page where rectangle bound with link will be created. |
| color | Color | The colour of rectangle for active click. |
| actionName | Enum[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
