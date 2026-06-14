---
title: "TextAbsorber.Visit"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextAbsorber method. Extracts text on the specified page"
type: docs
url: "/net/aspose.pdf.text/textabsorber/visit/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/textabsorber/visit/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:44:59+00:00"
---
## Visit(Page) {#visit_1}

Extracts text on the specified page

```csharp
public virtual void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | Pdf pocument page object. |

## Examples {#examples}

The example demonstrates how to extract text on the first PDF document page.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### See Also {#see-also}

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extracts text on the specified XForm.

```csharp
public virtual void Visit(XForm form)
```

| Parameter | Type | Description |
| --- | --- | --- |
| form | XForm | Pdf form object. |

## Examples {#examples-1}

The example demonstrates how to extract text on the first PDF document page.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### See Also {#see-also-1}

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extracts text on the specified document

```csharp
public virtual void Visit(Document pdf)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdf | Document | Pdf pocument object. |

## Examples {#examples-2}

The example demonstrates how to extract text on PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### See Also {#see-also-2}

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
