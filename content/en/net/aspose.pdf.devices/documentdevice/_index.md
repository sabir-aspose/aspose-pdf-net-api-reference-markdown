---
title: "Class DocumentDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.DocumentDevice class. Abstract class for all devices which is used to process the whole pdf document"
type: docs
url: "/net/aspose.pdf.devices/documentdevice/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.devices/documentdevice/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:09:59+00:00"
---
## DocumentDevice class {#documentdevice-class}

Abstract class for all devices which is used to process the whole pdf document.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Processes the whole document and saves results into stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Processes the whole document and saves results into file. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Perfoms some operation on the given page, e.g. converts page into graphic image. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Each device represents some operation on the document, e.g. we can convert pdf document into another format. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Processes certain pages of the document and saves results into file. |

### See Also {#see-also}

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)
