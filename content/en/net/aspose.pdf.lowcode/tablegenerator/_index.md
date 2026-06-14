---
title: "Class TableGenerator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.TableGenerator class. Represents Aspose.PDF TableGenerator plugin"
type: docs
url: "/net/aspose.pdf.lowcode/tablegenerator/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/tablegenerator/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:32:39+00:00"
---
## TableGenerator class {#tablegenerator-class}

Represents Aspose.PDF TableGenerator plugin.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [TableGenerator](tablegenerator/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.lowcode/tablegenerator/dispose/)() | Implementation of IDisposable. In fact, it is not necessary for TableGenerator. |
| [Process](../../aspose.pdf.lowcode/tablegenerator/process/)(IPluginOptions) | Starts the PdfGenerator processing with the specified parameters. |

## Examples {#examples}

The example demonstrates how to add table to PDF file.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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
