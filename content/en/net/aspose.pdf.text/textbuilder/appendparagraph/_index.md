---
title: "TextBuilder.AppendParagraph"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextBuilder method. Appends text paragraph to Pdf page"
type: docs
url: "/net/aspose.pdf.text/textbuilder/appendparagraph/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textbuilder/appendparagraph/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:45:00+00:00"
---
## TextBuilder.AppendParagraph method {#textbuilderappendparagraph-method}

Appends text paragraph to Pdf page.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textParagraph | TextParagraph | Text paragraph object. |

## Examples {#examples}

The example demonstrates how to create text paragraph object and append it to the Pdf page.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### See Also {#see-also}

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
