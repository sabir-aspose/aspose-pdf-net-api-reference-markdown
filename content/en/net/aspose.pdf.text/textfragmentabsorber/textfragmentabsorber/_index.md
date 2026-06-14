---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragmentAbsorber constructor. Initializes a new instance of the TextFragmentAbsorber that performs search of all text segments of the document or page"
type: docs
url: "/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:45:53+00:00"
---
## TextFragmentAbsorber() {#constructor}

Initializes a new instance of the [`TextFragmentAbsorber`](../) that performs search of all text segments of the document or page.

```csharp
public TextFragmentAbsorber()
```

## Remarks {#remarks}

Performs text search and provides access to search results via [`TextFragments`](../textfragments/) collection.

## Examples {#examples}

The example demonstrates how to find text on the first PDF document page and replace the text.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also {#see-also}

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initializes a new instance of the [`TextFragmentAbsorber`](../) with text edit options, that performs search of all text segments of the document or page.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

## Remarks {#remarks-1}

Performs text search and provides access to search results via [`TextFragments`](../textfragments/) collection.

## Examples {#examples-1}

The example demonstrates how to find all text fragments on the first PDF document page and replace font for them.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also {#see-also-1}

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified text phrase.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../) searches |

## Remarks {#remarks-2}

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments/) collection.

## Examples {#examples-2}

The example demonstrates how to find text on the first PDF document page and replace the text and it’s font.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also {#see-also-2}

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified System.Text.RegularExpressions.Regex class object.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex class object that the [`TextFragmentAbsorber`](../) searches |

## Remarks {#remarks-3}

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments/) collection.

## Examples {#examples-3}

The example demonstrates how to find text on the first PDF document page and replace the text and it’s font.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also {#see-also-3}

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified text phrase and text search options.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../) searches |
| textSearchOptions | TextSearchOptions | Text search options (Allows to turn on some search features. For example, search with regular expression) |

## Remarks {#remarks-4}

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments/) collection.

## Examples {#examples-4}

The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also {#see-also-4}

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified text phrase and text search options.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex class object that the [`TextFragmentAbsorber`](../) searches |
| textSearchOptions | TextSearchOptions | Text search options (Allows to turn on some search features.) |

## Remarks {#remarks-5}

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments/) collection.

## Examples {#examples-5}

The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also {#see-also-5}

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified text phrase and text search options.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regexes | Regex[] | Array of System.Text.RegularExpressions.Regex class object that the [`TextFragmentAbsorber`](../) searches. |
| textSearchOptions | TextSearchOptions | Text search options (Allows to turn on some search features.). |

## Remarks {#remarks-6}

Performs text search of the specified array of phrases and provides access to search results via [`RegexResults`](../regexresults/) dictionary.

## Examples {#examples-6}

The example demonstrates how to find text with array of regular expressions on the first PDF document page.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### See Also {#see-also-6}

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified text phrase, text search options and text edit options.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../) searches |
| textSearchOptions | TextSearchOptions | Text search options (Allows to turn on some search features. For example, search with regular expression) |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

## Remarks {#remarks-7}

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments/) collection.

## Examples {#examples-7}

The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also {#see-also-7}

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified text phrase and text edit options.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../) searches |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

## Remarks {#remarks-8}

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments/) collection.

### See Also {#see-also-8}

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initializes a new instance of the [`TextFragmentAbsorber`](../) class for the specified text phrase and text edit options.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex class object that the [`TextFragmentAbsorber`](../) searches |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

## Remarks {#remarks-9}

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments/) collection.

### See Also {#see-also-9}

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
