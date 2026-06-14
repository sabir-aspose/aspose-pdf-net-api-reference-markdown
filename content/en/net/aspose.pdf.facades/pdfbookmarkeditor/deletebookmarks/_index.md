---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfBookmarkEditor method. Deletes all bookmarks of the PDF document"
type: docs
url: "/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:42+00:00"
---
## DeleteBookmarks() {#deletebookmarks}

Deletes all bookmarks of the PDF document.

```csharp
public void DeleteBookmarks()
```

## Examples {#examples}

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Deletes the bookmark of the PDF document.

```csharp
public void DeleteBookmarks(string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | The title of bookmark deleted. |

## Examples {#examples-1}

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
