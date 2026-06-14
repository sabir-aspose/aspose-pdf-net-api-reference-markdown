---
title: "PdfBookmarkEditor.CreateBookmarkOfPage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfBookmarkEditor method. Creates bookmark for the specified page"
type: docs
url: "/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:40+00:00"
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Creates bookmark for the specified page.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmarkName | String | The specified bookmark name. |
| pageNumber | Int32 | The specified desination page. |

## Examples {#examples}

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Creates bookmarks for the specified pages.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmarkName | String[] | Bookmarks title array. |
| pageNumber | Int32[] | Bookmarks desination page array. |

## Examples {#examples-1}

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### See Also {#see-also-1}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
