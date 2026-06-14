---
title: "GraphicsAbsorber.SuppressUpdate"
second_title: "Aspose.PDF for .NET API Reference"
description: "GraphicsAbsorber method. Suppresses update for Contents and all Contents Was made for performance increase see also"
type: docs
url: "/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:47:49+00:00"
---
## GraphicsAbsorber.SuppressUpdate method {#graphicsabsorbersuppressupdate-method}

Suppresses update for [`Contents`](../../../aspose.pdf/page/contents/) and all [`Contents`](../../../aspose.pdf/xform/contents/) Was made for performance increase, see also .

```csharp
public void SuppressUpdate()
```

## Examples {#examples}

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### See Also {#see-also}

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)
