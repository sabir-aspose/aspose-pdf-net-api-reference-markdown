---
title: "PdfContentEditor.DeleteStampById"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Deletes stamp on the specified page by stamp ID"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:11+00:00"
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Deletes stamp on the specified page by stamp ID.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Page number where stamp will be deleted. |
| stampId | Int32 | Identifier of stanp which should be deleted. |

## Examples {#examples}

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Delete stamp by ID from all pages of the document.

```csharp
public void DeleteStampById(int stampId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stampId | Int32 | Identifier of stamp which should be deleted. |

## Examples {#examples-1}

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### See Also {#see-also-1}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
