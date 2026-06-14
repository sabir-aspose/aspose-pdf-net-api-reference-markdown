---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextPdfComparer method. Compares two documents page by page. The documents are compared as a whole. Before comparing text the texts of document pages are combined into one text"
type: docs
url: "/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:08:55+00:00"
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |

### Return Value {#return-value}

List of changes.

### See Also {#see-also}

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Compares two documents page by page. The result is saved in a PDF file. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |
| resultPdfDocumentPath | String | Path to the pdf file to save the comparison results. |

### Return Value {#return-value-1}

List of changes.

### See Also {#see-also-1}

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)
