---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Returns the view preference"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:19+00:00"
---
## PdfContentEditor.GetViewerPreference method {#pdfcontenteditorgetviewerpreference-method}

Returns the view preference.

```csharp
public int GetViewerPreference()
```

### Return Value {#return-value}

Returns set of ViewerPrefernece flags

## Examples {#examples}

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
