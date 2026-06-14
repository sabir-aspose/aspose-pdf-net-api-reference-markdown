---
title: "Class MarkdownDiffOutputGenerator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator class. Represents a class for generating markdown representation of texts differences. Because of the markdown syntax it is not possible to show changes to whitespace characters. Selection of changes makes adding whitespace characters around formatting otherwise markdown viewer will not correctly display the text. Deleted line breaks are indicated by paragraph mark"
type: docs
url: "/net/aspose.pdf.comparison/markdowndiffoutputgenerator/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.comparison/markdowndiffoutputgenerator/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:08:29+00:00"
---
## MarkdownDiffOutputGenerator class {#markdowndiffoutputgenerator-class}

Represents a class for generating markdown representation of texts differences. Because of the markdown syntax, it is not possible to show changes to whitespace characters. Selection of changes makes adding whitespace characters around formatting, otherwise markdown viewer will not correctly display the text. Deleted line breaks are indicated by - paragraph mark.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List<DiffOperation>) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List<List<DiffOperation>>) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List<DiffOperation>, string) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List<List<DiffOperation>>, string) | Generates the output based on the differences between texts and saves it to a file. |

### See Also {#see-also}

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)
