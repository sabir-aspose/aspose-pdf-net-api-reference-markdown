---
title: "Class Optimizer"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Optimizer class. Represents Optimizer plugin"
type: docs
url: "/net/aspose.pdf.lowcode/optimizer/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/optimizer/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:30:50+00:00"
---
## Optimizer class {#optimizer-class}

Represents `Optimizer` plugin.

```csharp
public sealed class Optimizer : IPlugin
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [Optimizer](optimizer/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.lowcode/optimizer/process/)(IPluginOptions) | Starts the `Optimizer` processing with the specified parameters. |

## Examples {#examples}

The example demonstrates how to optimize PDF document.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### See Also {#see-also}

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)
