---
title: "TextBuilder.AppendText"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextBuilder method. Appends text fragment to Pdf page"
type: docs
url: "/net/aspose.pdf.text/textbuilder/appendtext/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textbuilder/appendtext/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:45:01+00:00"
---
## AppendText(TextFragment) {#appendtext}

Appends text fragment to Pdf page

```csharp
public void AppendText(TextFragment textFragment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textFragment | TextFragment | Text fragment object. |

## Examples {#examples}

The example demonstrates how to create text fragment object, customize it’s text segments and append it to the Pdf page.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### See Also {#see-also}

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List<TextFragment>) {#appendtext_1}

Appends list of text fragments to Pdf page.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textFragments | List`1 | Collection of text fragments |

### See Also {#see-also-1}

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
