---
title: "Page.Rect"
second_title: "Aspose.PDF for .NET API Reference"
description: "Page property. Gets or sets rectangle of the page. For get page crop box is returned if specified otherwise page media box is returned. For set page media box always set. Please note that this property dont consider page rotation. To get page rectangle considering rotation please use ActualRect"
type: docs
url: "/net/aspose.pdf/page/rect/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/page/rect/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:04:12+00:00"
---
## Page.Rect property {#pagerect-property}

Gets or sets rectangle of the page. For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. Please note that this property don’t consider page rotation. To get page rectangle considering rotation please use ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Examples {#examples}

Example demonstrates how to get page rectangle:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### See Also {#see-also}

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
