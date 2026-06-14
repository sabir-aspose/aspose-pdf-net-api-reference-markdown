---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfBookmarkEditor method. Exports bookmarks to XML file"
type: docs
url: "/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:43+00:00"
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exports bookmarks to XML file.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | String | The output XML file. |

## Examples {#examples}

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### See Also {#see-also}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exports bookmarks to XML stream.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Output stream where data will be stored. |

### See Also {#see-also-1}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
