---
title: "HeaderElement.AddEntryToTocPage"
second_title: "Aspose.PDF for .NET API Reference"
description: "HeaderElement method. Creates a header on the specified Table of Contents TOC page and associates it with a TOCI element"
type: docs
url: "/net/aspose.pdf.logicalstructure/headerelement/addentrytotocpage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.logicalstructure/headerelement/addentrytotocpage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:25:43+00:00"
---
## AddEntryToTocPage(Page, TOCIElement) {#addentrytotocpage_1}

Creates a header on the specified Table of Contents (TOC) page and associates it with a TOCI element.

```csharp
public void AddEntryToTocPage(Page tocPage, TOCIElement tocEntry)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tocPage | Page | The [`Page`](../../../aspose.pdf/page/) object representing the TOC page where the header should be created. |
| tocEntry | TOCIElement | The [`TOCIElement`](../../tocielement/) serving as the TOC entry to associate with the header being created. |

## Remarks {#remarks}

This method ensures that the header is properly linked to a TOC page and a TOCI element, maintaining the document’s logical hierarchy and supporting navigation in tagged PDF structures.

### See Also {#see-also}

* class [Page](../../../aspose.pdf/page/)
* class [TOCIElement](../../tocielement/)
* class [HeaderElement](../)
* namespace [Aspose.Pdf.LogicalStructure](../../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../../)

---

## AddEntryToTocPage(Page, ListLIElement) {#addentrytotocpage}

Creates a header on the specified Table of Contents (TOC) page and associates it with a TOCI element.

```csharp
public void AddEntryToTocPage(Page tocPage, ListLIElement tocEntry)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tocPage | Page | The [`Page`](../../../aspose.pdf/page/) object representing the TOC page where the header should be created. |
| tocEntry | ListLIElement | The [`ListLIElement`](../../listlielement/) object acting as the TOCI entry to associate with the created header on the specified TOC page. |

## Remarks {#remarks-1}

This overload addresses scenarios involving nested Table of Contents (TOC) structures, as specified in PDF/UA and PDF 1.7 standards, where a `TOCI` element cannot be a child of another `TOCI` or where a `TOC` cannot be nested directly under a `TOCI`. To maintain compliance with these structural requirements, nested TOC entries should be represented using `List` and `ListLIElement` elements. This method facilitates the association of the header element with such a [`ListLIElement`](../../listlielement/) on the designated TOC page, ensuring proper logical structuring and enhancing navigation capabilities in tagged PDF documents.

### See Also {#see-also-1}

* class [Page](../../../aspose.pdf/page/)
* class [ListLIElement](../../listlielement/)
* class [HeaderElement](../)
* namespace [Aspose.Pdf.LogicalStructure](../../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../../)
