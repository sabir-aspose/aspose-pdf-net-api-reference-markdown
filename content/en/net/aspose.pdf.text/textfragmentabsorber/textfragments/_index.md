---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragmentAbsorber property. Gets collection of search occurrences that are presented with TextFragment objects"
type: docs
url: "/net/aspose.pdf.text/textfragmentabsorber/textfragments/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textfragmentabsorber/textfragments/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:45:54+00:00"
---
## TextFragmentAbsorber.TextFragments property {#textfragmentabsorbertextfragments-property}

Gets collection of search occurrences that are presented with [`TextFragment`](../../textfragment/) objects.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Examples {#examples}

The example demonstrates how to find text on the first PDF document page and replace all search occurrences with new text.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also {#see-also}

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
