---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfBookmarkEditor method. Modifys bookmark title according to the specified bookmark title"
type: docs
url: "/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:45+00:00"
---
## PdfBookmarkEditor.ModifyBookmarks method {#pdfbookmarkeditormodifybookmarks-method}

Modifys bookmark title according to the specified bookmark title.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sTitle | String | Source bookmark title. |
| dTitle | String | Modified bookmark title. |

## Examples {#examples}

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
