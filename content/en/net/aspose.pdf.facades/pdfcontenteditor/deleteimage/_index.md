---
title: "PdfContentEditor.DeleteImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Deletes the specified images on the specified page"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:09+00:00"
---
## DeleteImage(int, int[]) {#deleteimage_1}

Deletes the specified images on the specified page.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | The number of page on which images must be deleted. |
| index | Int32[] | An array repsents images’ indexes. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Deletes all images from PDF document.

```csharp
public void DeleteImage()
```

## Examples {#examples-1}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
