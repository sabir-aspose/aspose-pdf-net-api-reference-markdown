---
title: "Enum LineJoin"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.LineJoin enum. The line join style shall specify the shape to be used at the corners of paths that are stroked"
type: docs
url: "/net/aspose.pdf.operators/linejoin/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.operators/linejoin/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:35:05+00:00"
---
## LineJoin enumeration {#linejoin-enumeration}

The line join style shall specify the shape to be used at the corners of paths that are stroked.

```csharp
public enum LineJoin
```

### Values {#values}

| Name | Value | Description |
| --- | --- | --- |
| MiterJoin | `0` | Miter join. The outer edges of the strokes for the two segments shall be extended until they meet at an angle, as in a picture frame. If the segments meet at too sharp an angle as defined by the miter limit parameter (see 8.4.3.5, “Miter Limit”), a bevel join shall be used instead. |
| RoundJoin | `1` | Round join. An arc of a circle with a diameter equal to the line width shall be drawn around the point where the two segments meet, connecting the outer edges of the strokes for the two segments. This pieslice-shaped figure shall be filled in, producing a rounded corner. |
| BevelJoin | `2` | Bevel join. The two segments shall be finished with butt caps (see 8.4.3.3, “Line Cap Style”) and the resulting notch beyond the ends of the segments shall be filled with a triangle. |

### See Also {#see-also}

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)
