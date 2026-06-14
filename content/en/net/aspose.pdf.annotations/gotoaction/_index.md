---
title: "Class GoToAction"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.GoToAction class. Represents a goto action that changes the view to a specified destination page location and magnification factor"
type: docs
url: "/net/aspose.pdf.annotations/gotoaction/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.annotations/gotoaction/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:01:58+00:00"
---
## GoToAction class {#gotoaction-class}

Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor).

```csharp
public class GoToAction : PdfAction
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | Constructor. |
| [GoToAction](gotoaction/#constructor_3)(Page) | Constructor for GoToAction class. |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | Action which linked with Named Destination. |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | Constructor for GoToAction class. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | Gets or sets the destination to jump to. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Next actions in sequence. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Gets string for ECMAScript Action. |

### See Also {#see-also}

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)
