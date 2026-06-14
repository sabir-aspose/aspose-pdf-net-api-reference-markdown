---
title: "PdfPageEditor.GetPageRotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor method. Returns the rotation of specified page"
type: docs
url: "/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:18:22+00:00"
---
## PdfPageEditor.GetPageRotation method {#pdfpageeditorgetpagerotation-method}

Returns the rotation of specified page.

```csharp
public int GetPageRotation(int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | Page index. Document pages are numbered from 1. |

### Return Value {#return-value}

Page rotation in degrees.

## Examples {#examples}

The following example demonstrates how to get page rotation:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### See Also {#see-also}

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
