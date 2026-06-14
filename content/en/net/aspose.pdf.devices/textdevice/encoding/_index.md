---
title: "TextDevice.Encoding"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextDevice property. Gets or sets encoding of extracted text"
type: docs
url: "/net/aspose.pdf.devices/textdevice/encoding/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.devices/textdevice/encoding/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:10:25+00:00"
---
## TextDevice.Encoding property {#textdeviceencoding-property}

Gets or sets encoding of extracted text.

```csharp
public Encoding Encoding { get; set; }
```

## Examples {#examples}

The example demonstrates how to represent extracted text in UTF-8 encoding.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### See Also {#see-also}

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)
