---
title: "Class Element"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LogicalStructure.Element class. Represents a base class for element in logical structure"
type: docs
url: "/net/aspose.pdf.logicalstructure/element/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.logicalstructure/element/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:25:30+00:00"
---
## Element class {#element-class}

Represents a base class for element in logical structure.

```csharp
public abstract class Element
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gets children collection of Element objects. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Get parent element. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Append Element to collection of children. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Clear all childs. |
| [FindElements<T>](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Find Elements of a given type |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insert Element to collection of children at specified index. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove child at. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Bind a structure element to the Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Bind a structure element to the Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Bind a structure element to the content stream BDC operator. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Bind a structure element to the content stream XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Bind a structure element to the XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Returns a string that represents the current object. |

### See Also {#see-also}

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)
