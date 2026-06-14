---
title: "PdfPageEditor.GetPageSize"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor method. Returns the page size of the specified page"
type: docs
url: "/net/aspose.pdf.facades/pdfpageeditor/getpagesize/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfpageeditor/getpagesize/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:18:23+00:00"
---
## PdfPageEditor.GetPageSize method {#pdfpageeditorgetpagesize-method}

Returns the page size of the specified page.

```csharp
public PageSize GetPageSize(int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | Page index. Document pages are numbered from 1. |

### Return Value {#return-value}

Result is instance of PageSize. Use Width and Height properties of the returned object to get page width and height.

## Examples {#examples}

The following example demonstrates using of GetPageSize method:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### See Also {#see-also}

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
