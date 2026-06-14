---
title: "TextAbsorber.TextAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextAbsorber constructor. Initializes a new instance of the TextAbsorber"
type: docs
url: "/net/aspose.pdf.text/textabsorber/textabsorber/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textabsorber/textabsorber/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:44:58+00:00"
---
## TextAbsorber() {#constructor}

Initializes a new instance of the [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Remarks {#remarks}

Performs text extraction and provides access to the extracted text via [`Text`](../text/) object.

## Examples {#examples}

The example demonstrates how to extract text from all pages of the PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### See Also {#see-also}

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Initializes a new instance of the [`TextAbsorber`](../) with extraction options.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Text extraction options |

## Remarks {#remarks-1}

Performs text extraction and provides access to the extracted text via [`Text`](../text/) object.

## Examples {#examples-1}

The example demonstrates how to extract text from all pages of the PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### See Also {#see-also-1}

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Initializes a new instance of the [`TextAbsorber`](../) with extraction and text search options.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Text extraction options |
| textSearchOptions | TextSearchOptions | Text search options |

## Remarks {#remarks-2}

Performs text extraction and provides access to the extracted text via [`Text`](../text/) object.

### See Also {#see-also-2}

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Initializes a new instance of the [`TextAbsorber`](../) with text search options.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Text search options |

## Remarks {#remarks-3}

Performs text extraction and provides access to the extracted text via [`Text`](../text/) object.

### See Also {#see-also-3}

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
