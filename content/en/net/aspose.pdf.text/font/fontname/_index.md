---
title: "Font.FontName"
second_title: "Aspose.PDF for .NET API Reference"
description: "Font property. Gets font name of the Font object"
type: docs
url: "/net/aspose.pdf.text/font/fontname/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/font/fontname/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:43:17+00:00"
---
## Font.FontName property {#fontfontname-property}

Gets font name of the [`Font`](../) object.

```csharp
public string FontName { get; }
```

## Examples {#examples}

The example demonstrates how to search text on first page and view font name of a first text occurrence.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### See Also {#see-also}

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
