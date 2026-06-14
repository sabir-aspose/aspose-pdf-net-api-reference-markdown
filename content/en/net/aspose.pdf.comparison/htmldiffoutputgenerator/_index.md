---
title: "Class HtmlDiffOutputGenerator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by paragraph mark"
type: docs
url: "/net/aspose.pdf.comparison/htmldiffoutputgenerator/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.comparison/htmldiffoutputgenerator/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:08:14+00:00"
---
## HtmlDiffOutputGenerator class {#htmldiffoutputgenerator-class}

Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by paragraph mark.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Creates an instance of `HtmlDiffOutputGenerator` class. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Creates an instance of `HtmlDiffOutputGenerator` class. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Gets and sets the CSS-style string for Delete operation. Example: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Gets and sets the CSS-style string for Equal operation. Example: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Gets and sets the CSS-style string for Insert operation. Example: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Get or set text-decoration: line-through style for the delete operation. Default value is `False`. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List<DiffOperation>) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List<List<DiffOperation>>) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List<DiffOperation>, string) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List<List<DiffOperation>>, string) | Generates the output based on the differences between texts and saves it to a file. |

### See Also {#see-also}

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)
