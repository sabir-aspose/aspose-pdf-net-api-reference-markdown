---
title: "Class BasicSetColorAndPatternOperator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Operators.BasicSetColorAndPatternOperator class. Base operator for all Set Color operators"
type: docs
url: "/net/aspose.pdf.operators/basicsetcolorandpatternoperator/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.operators/basicsetcolorandpatternoperator/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:33:24+00:00"
---
## BasicSetColorAndPatternOperator class {#basicsetcolorandpatternoperator-class}

Base operator for all Set Color operators.

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Gets red component of color |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Gets cyan component of CMYK color. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Gets array of color components. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Gets green component of color |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gets black component of gray color. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operator index in page operators list. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Gets black component of CMYK color. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Gets magenta component of CMYK color. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Gets Pattern Name. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Gets red component of color |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Gets yellow component of CMYK color. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accepts visitor IOperatorSelector which provides operators processing. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Retirns color specified by the operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returns text of operator and its parameters. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compares this instance with the given object. |

### See Also {#see-also}

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)
