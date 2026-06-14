---
title: "Font.IsAccessible"
second_title: "Aspose.PDF for .NET API Reference"
description: "Font property. Gets indicating whether the font is present installed in the system"
type: docs
url: "/net/aspose.pdf.text/font/isaccessible/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/font/isaccessible/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:43:19+00:00"
---
## Font.IsAccessible property {#fontisaccessible-property}

Gets indicating whether the font is present (installed) in the system.

```csharp
public bool IsAccessible { get; }
```

## Remarks {#remarks}

Some operations are not available with fonts that could not be found in the system.

## Examples {#examples}

The example demonstrates how to search text on first page and get the value that indicates whether the font is installed in the system.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### See Also {#see-also}

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
