---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragmentAbsorber property. Gets or sets search options. The options enable search using regular expressions"
type: docs
url: "/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:45:55+00:00"
---
## TextFragmentAbsorber.TextSearchOptions property {#textfragmentabsorbertextsearchoptions-property}

Gets or sets search options. The options enable search using regular expressions.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Examples {#examples}

The example demonstrates how to perform search text using regular expression.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also {#see-also}

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
