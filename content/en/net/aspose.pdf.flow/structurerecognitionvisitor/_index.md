---
title: "Class StructureRecognitionVisitor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Flow.StructureRecognitionVisitor class. Base class for a custom document structure recognition visitor"
type: docs
url: "/net/aspose.pdf.flow/structurerecognitionvisitor/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.flow/structurerecognitionvisitor/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:20:28+00:00"
---
## StructureRecognitionVisitor class {#structurerecognitionvisitor-class}

Base class for a custom document structure recognition visitor

```csharp
public class StructureRecognitionVisitor : IStructureRecognitionVisitor
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [StructureRecognitionVisitor](structurerecognitionvisitor/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| virtual [EndDocument](../../aspose.pdf.flow/structurerecognitionvisitor/enddocument/)() | Signals the end of document processing. |
| virtual [Recognize](../../aspose.pdf.flow/structurerecognitionvisitor/recognize/#recognize)(Document) | Start recognition of document |
| virtual [Recognize](../../aspose.pdf.flow/structurerecognitionvisitor/recognize/#recognize_1)(Page) | Start recognition of page |
| virtual [StartDocument](../../aspose.pdf.flow/structurerecognitionvisitor/startdocument/)() | Called when the document traversal starts. |
| virtual [VisitParagraph](../../aspose.pdf.flow/structurerecognitionvisitor/visitparagraph/)(BaseParagraph) | Called when a paragraph node is visited. |
| virtual [VisitSectionEnd](../../aspose.pdf.flow/structurerecognitionvisitor/visitsectionend/)(MarginInfo) | Visits the end of a recognized section in the document. |
| virtual [VisitTable](../../aspose.pdf.flow/structurerecognitionvisitor/visittable/)(Table) | Visits a recognized table in the document structure. |

### See Also {#see-also}

* interface [IStructureRecognitionVisitor](../istructurerecognitionvisitor/)
* namespace [Aspose.Pdf.Flow](../../aspose.pdf.flow/)
* assembly [Aspose.PDF](../../)
