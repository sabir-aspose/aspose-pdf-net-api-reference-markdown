---
title: "GraphicalPdfComparer.ComparePagesToImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "GraphicalPdfComparer method. Compares pages graphically. The comparison result is placed in a image"
type: docs
url: "/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:08:10+00:00"
---
## GraphicalPdfComparer.ComparePagesToImage method {#graphicalpdfcomparercomparepagestoimage-method}

Compares pages graphically. The comparison result is placed in a image.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page to compare. |
| page2 | Page | The second page to compare. |
| resultImagePath | String | The path to target image file. |

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentException | If the pages being compared are of different sizes. If resultImagePath is null or empty string. There is unknown saving image format. |

### See Also {#see-also}

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)
