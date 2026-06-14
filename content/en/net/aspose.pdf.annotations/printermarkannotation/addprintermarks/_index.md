---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "Aspose.PDF for .NET API Reference"
description: "PrinterMarkAnnotation method. Adds printers marks to all pages in the specified document"
type: docs
url: "/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:05:29+00:00"
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Adds printer’s marks to all pages in the specified document.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | The document to which the printer’s marks will be added. |
| marksKind | PrinterMarksKind | The kind of printer’s marks to add. |

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when the *document* is null. |

## Remarks {#remarks}

This method adds various types of printer’s marks based on the provided [`PrinterMarksKind`](../../printermarkskind/) flags. If None is provided, no marks are added.

### See Also {#see-also}

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Adds printer’s marks to the specified page.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The page to which the printer’s marks will be added. |
| marksKind | PrinterMarksKind | The kind of printer’s marks to add. |

### Exceptions {#exceptions-1}

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when the *page* is null. |

## Remarks {#remarks-1}

This method adds various types of printer’s marks based on the provided [`PrinterMarksKind`](../../printermarkskind/) flags. If None is provided, no marks are added.

### See Also {#see-also-1}

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)
