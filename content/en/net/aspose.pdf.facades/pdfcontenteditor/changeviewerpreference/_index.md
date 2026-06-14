---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Changes the view preference"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:50+00:00"
---
## PdfContentEditor.ChangeViewerPreference method {#pdfcontenteditorchangeviewerpreference-method}

Changes the view preference.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parameter | Type | Description |
| --- | --- | --- |
| viewerAttribution | Int32 | The view attribution defined in the ViewerPreference class. |

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
