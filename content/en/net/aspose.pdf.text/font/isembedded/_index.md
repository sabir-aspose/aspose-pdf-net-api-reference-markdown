---
title: "Font.IsEmbedded"
second_title: "Aspose.PDF for .NET API Reference"
description: "Font property. Gets or sets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded"
type: docs
url: "/net/aspose.pdf.text/font/isembedded/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/font/isembedded/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:43:20+00:00"
---
## Font.IsEmbedded property {#fontisembedded-property}

Gets or sets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded

```csharp
public bool IsEmbedded { get; set; }
```

## Examples {#examples}

The following example demonstrates how to find a font, mark it as embedded, search text on the document’s page and replace the text font.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also {#see-also}

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
