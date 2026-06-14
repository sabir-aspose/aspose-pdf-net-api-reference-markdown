---
title: "PdfPageEditor.MovePosition"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor method. Moves the origin from 0 0 to the point that appointted. The origin is leftbottom and the unit is point1 inch 72 points"
type: docs
url: "/net/aspose.pdf.facades/pdfpageeditor/moveposition/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfpageeditor/moveposition/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:18:27+00:00"
---
## PdfPageEditor.MovePosition method {#pdfpageeditormoveposition-method}

Moves the origin from (0, 0) to the point that appointted. The origin is left-bottom and the unit is point(1 inch = 72 points).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| moveX | Single | X-coordinate. |
| moveY | Single | Y-coordinate. |

## Examples {#examples}

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### See Also {#see-also}

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
