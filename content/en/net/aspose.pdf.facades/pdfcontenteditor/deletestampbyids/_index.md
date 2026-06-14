---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Deletes stamps with specified IDs from all pages of the document"
type: docs
url: "/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:15:11+00:00"
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Deletes stamps with specified IDs from all pages of the document.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stampIds | Int32[] | Array of stamp IDs. |

## Examples {#examples}

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### See Also {#see-also}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Deletes stamps on the specified page by multiple stamp IDs.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Page number where stamps will be deleted. |
| stampIds | Int32[] | Array of stamp IDs. |

## Examples {#examples-1}

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### See Also {#see-also-1}

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
