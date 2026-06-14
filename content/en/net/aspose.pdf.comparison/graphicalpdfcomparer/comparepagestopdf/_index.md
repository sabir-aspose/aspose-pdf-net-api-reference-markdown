---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "GraphicalPdfComparer method. Compares pages graphically. The comparison result is placed in a PDF document"
type: docs
url: "/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:08:11+00:00"
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Compares pages graphically. The comparison result is placed in a PDF document.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page. |
| page2 | Page | The second page. |
| resultPdfPath | String | The path to target pdf file. |

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes. If resultPdfPath is null or empty string. |

### See Also {#see-also}

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Compares pages graphically. The comparison result is placed in a PDF document.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page. |
| page2 | Page | The second page. |
| pdfDocument | Document | The pdf document instance. |

### Exceptions {#exceptions-1}

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes. |

### See Also {#see-also-1}

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)
