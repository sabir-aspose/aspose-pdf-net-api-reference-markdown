---
title: "Class Operator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operator class. Abstract class representing operator"
type: docs
url: "/net/aspose.pdf/operator/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/operator/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:01:55+00:00"
---
## Operator class {#operator-class}

Abstract class representing operator.

```csharp
public abstract class Operator
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accepts visitor IOperatorSelector which provides operators processing. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |

### See Also {#see-also}

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
