---
title: "TextFragment.Position"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragment property. Gets or sets text position for text represented with TextFragment object"
type: docs
url: "/net/aspose.pdf.text/textfragment/position/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textfragment/position/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:45:36+00:00"
---
## TextFragment.Position property {#textfragmentposition-property}

Gets or sets text position for text, represented with [`TextFragment`](../) object.

```csharp
public Position Position { get; set; }
```

## Examples {#examples}

The example demonstrates how to view placement of a text, represented by [`TextFragment`](../) object.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View text and placement info of first text occurrence
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));
```

### See Also {#see-also}

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
