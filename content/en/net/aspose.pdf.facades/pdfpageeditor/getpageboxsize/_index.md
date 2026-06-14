---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor method. Returns size of specified box in document"
type: docs
url: "/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:18:21+00:00"
---
## PdfPageEditor.GetPageBoxSize method {#pdfpageeditorgetpageboxsize-method}

Returns size of specified box in document.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | Page index. Document pages are numbered from 1. |
| pageBoxName | String | Box type name. Valid values are: “art”, “bleed”, “crop”, “media”, “trim”. |

### Return Value {#return-value}

Rectangle which contains requested box.

## Examples {#examples}

The following example demonstrates how to get media box of the 1st page:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### See Also {#see-also}

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
