---
title: "Document.Actions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document property. Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing BeforSaving etc. actions"
type: docs
url: "/net/aspose.pdf/document/actions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/document/actions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:53:56+00:00"
---
## Document.Actions property {#documentactions-property}

Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions.

```csharp
public DocumentActionCollection Actions { get; }
```

## Examples {#examples}

This example demonstrates how to obtain after open action of the document:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### See Also {#see-also}

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
