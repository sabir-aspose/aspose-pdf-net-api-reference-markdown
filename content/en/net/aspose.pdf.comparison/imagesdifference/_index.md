---
title: "Class ImagesDifference"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.ImagesDifference class. Represents the result class of comparing two PDF pages"
type: docs
url: "/net/aspose.pdf.comparison/imagesdifference/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.comparison/imagesdifference/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:08:20+00:00"
---
## ImagesDifference class {#imagesdifference-class}

Represents the result class of comparing two PDF pages.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Gets the difference array. This array is similar to the original image data array obtained as a result of the LockBits method. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | The height of difference. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Gets the image of first compared page. The image has a pixel format is 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | The stride of difference image data. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Converts the difference array to a bitmap image using the specified colors. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Performs any necessary clean up operations before the object is destroyed. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Returns a new bitmap representing the destination image by applying the difference array to the source image. |

### See Also {#see-also}

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)
