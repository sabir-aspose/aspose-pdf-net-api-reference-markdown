---
title: "TextDevice.ExtractionOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextDevice property. Gets or sets text extraction options"
type: docs
url: "/net/aspose.pdf.devices/textdevice/extractionoptions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.devices/textdevice/extractionoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:10:26+00:00"
---
## TextDevice.ExtractionOptions property {#textdeviceextractionoptions-property}

Gets or sets text extraction options.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Examples {#examples}

The example demonstrates how to extracted text in raw order.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### See Also {#see-also}

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)
