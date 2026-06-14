---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfBookmarkEditor method. Imports bookmarks to the document from XML file"
type: docs
url: "/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:44+00:00"
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Imports bookmarks to the document from XML file.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | String | The XML file containing bookmarks list. |

## Examples {#examples}

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Imports bookmarks to the document from XML file.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream with bookmarks data. |

### See Also {#see-also-1}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
