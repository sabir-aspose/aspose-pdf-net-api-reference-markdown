---
title: "PdfPageEditor.Save"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfPageEditor method. Saves changed document into file"
type: docs
url: "/net/aspose.pdf.facades/pdfpageeditor/save/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfpageeditor/save/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:18:33+00:00"
---
## Save(string) {#save_1}

Saves changed document into file.

```csharp
public override void Save(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | Path to file where document will be saved. |

## Examples {#examples}

The following sample demonstrates how to save changed PDF document

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### See Also {#see-also}

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Saves changed document into stream.

```csharp
public override void Save(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where changed PDF document will be saved. |

## Examples {#examples-1}

The following sample demonstrates how to save changed PDF document into stream.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### See Also {#see-also-1}

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
