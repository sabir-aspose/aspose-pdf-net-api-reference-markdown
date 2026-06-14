---
title: "FontRepository.FindFont"
second_title: "Aspose.PDF for .NET API Reference"
description: "FontRepository method. Searches and returns font with specified font name"
type: docs
url: "/net/aspose.pdf.text/fontrepository/findfont/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/fontrepository/findfont/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:43:33+00:00"
---
## FindFont(string) {#findfont}

Searches and returns font with specified font name.

```csharp
public static Font FindFont(string fontName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | String | Font name. |

### Return Value {#return-value}

Font object.

## Examples {#examples}

The example demonstrates how to find font and replace the font of text of first page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also {#see-also}

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Searches and returns font with specified font name ignoring or honoring case sensitivity.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | String | Font name. |
| ignoreCase | Boolean | case sensitivity |

### Return Value {#return-value-1}

Font object.

## Examples {#examples-1}

The example demonstrates how to find font and replace the font of text of first page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also {#see-also-1}

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Searches and returns font with specified font name and font style.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Font family name. |
| stl | FontStyles | Font style value. |

### Return Value {#return-value-2}

Font object corresponding to search request parameters.

## Examples {#examples-2}

The example demonstrates how to find font and replace the font of text of first page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also {#see-also-2}

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Searches and returns font with specified font name and font style ignoring or honoring case sensitivity.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Font family name. |
| stl | FontStyles | Font style value. |
| ignoreCase | Boolean | case sensitivity |

### Return Value {#return-value-3}

Font object corresponding to search request parameters.

## Examples {#examples-3}

The example demonstrates how to find font and replace the font of text of first page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also {#see-also-3}

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
