---
title: "Page.Contents"
second_title: "Aspose.PDF for .NET API Reference"
description: "Page property. Gets collection of operators in the content stream of the page. OperatorCollection"
type: docs
url: "/net/aspose.pdf/page/contents/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/page/contents/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:03:48+00:00"
---
## Page.Contents property {#pagecontents-property}

Gets collection of operators in the content stream of the page. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Examples {#examples}

Example is demonstrates how to scan operators stream of page.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### See Also {#see-also}

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
