---
title: "TextDevice.Process"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextDevice method. Convert page and save it as text stream"
type: docs
url: "/net/aspose.pdf.devices/textdevice/process/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.devices/textdevice/process/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:10:27+00:00"
---
## TextDevice.Process method {#textdeviceprocess-method}

Convert page and save it as text stream.

```csharp
public override void Process(Page page, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The page to convert. |
| output | Stream | Result stream. |

## Examples {#examples}

The example demonstrates how to extract text on the first PDF document page.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### See Also {#see-also}

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)
