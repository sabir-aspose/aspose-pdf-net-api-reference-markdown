---
title: "Class TocGenerator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.TocGenerator class. Represents Aspose.PDF TocGenerator plugin"
type: docs
url: "/net/aspose.pdf.lowcode/tocgenerator/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/tocgenerator/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:33:12+00:00"
---
## TocGenerator class {#tocgenerator-class}

Represents Aspose.PDF TocGenerator plugin.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [TocGenerator](tocgenerator/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.lowcode/tocgenerator/dispose/)() | Implementation of IDisposable. In fact, it is not necessary for TocGenerator. |
| [Process](../../aspose.pdf.lowcode/tocgenerator/process/)(IPluginOptions) | Starts the PdfGenerator processing with the specified parameters. |

## Examples {#examples}

The example demonstrates how to add TOC to PDF file.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### See Also {#see-also}

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)
