---
title: "TextFragmentAbsorber.Visit"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragmentAbsorber method. Performs search on the specified page"
type: docs
url: "/net/aspose.pdf.text/textfragmentabsorber/visit/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textfragmentabsorber/visit/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:45:56+00:00"
---
## Visit(Page) {#visit_1}

Performs search on the specified page.

```csharp
public override void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | PDF document page object. |

## Examples {#examples}

The example demonstrates how to find text on the first PDF document page and replace the text.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also {#see-also}

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Performs search on the specified document.

```csharp
public override void Visit(Document pdf)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdf | Document | PDF document object. |

## Examples {#examples-1}

The example demonstrates how to find text on PDF document and replace text of all search occurrences.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also {#see-also-1}

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Performs search on the specified form object.

```csharp
public void Visit(XForm xForm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xForm | XForm | Pdf form object. |

### See Also {#see-also-2}

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
