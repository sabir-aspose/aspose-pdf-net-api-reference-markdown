---
title: "Page.Resources"
second_title: "Aspose.PDF for .NET API Reference"
description: "Page property. Gets page resources. Resources object contains collections of images forms and fonts. Resources"
type: docs
url: "/net/aspose.pdf/page/resources/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/page/resources/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:04:14+00:00"
---
## Page.Resources property {#pageresources-property}

Gets page resources. Resources object contains collections of images, forms and fonts. `Resources`

```csharp
public Resources Resources { get; }
```

## Examples {#examples}

Example demonstrates scan through page images:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### See Also {#see-also}

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
