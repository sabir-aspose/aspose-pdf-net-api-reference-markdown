---
title: "TextPdfComparer.CompareDocumentsPageByPage"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextPdfComparer method. Compares two documents page by page"
type: docs
url: "/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:08:54+00:00"
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Compares two documents page by page.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document.. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |

### Return Value {#return-value}

List of changes by page.

### See Also {#see-also}

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Compares two documents page by page. The result is saved in a PDF file.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document.. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |
| resultPdfDocumentPath | String | Path to the pdf file to save the comparison results. |

### Return Value {#return-value-1}

List of changes by page.

### See Also {#see-also-1}

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)
