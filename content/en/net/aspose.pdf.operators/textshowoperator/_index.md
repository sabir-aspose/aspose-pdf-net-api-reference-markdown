---
title: "Class TextShowOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.TextShowOperator class. Abstract base class for all operators which used to out text Tj TJ etc"
type: docs
url: "/net/aspose.pdf.operators/textshowoperator/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.operators/textshowoperator/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:37:58+00:00"
---
## TextShowOperator class {#textshowoperator-class}

Abstract base class for all operators which used to out text (Tj, TJ, etc).

```csharp
public class TextShowOperator : TextOperator
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Initializes TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Initializes TextShowOperator which allows to pass TextProperties. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Gets text which operator out on the page. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accepts visitor object to process operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also {#see-also}

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)
