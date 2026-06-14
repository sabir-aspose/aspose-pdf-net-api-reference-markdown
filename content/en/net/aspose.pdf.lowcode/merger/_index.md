---
title: "Class Merger"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Merger class. Represents Merger plugin"
type: docs
url: "/net/aspose.pdf.lowcode/merger/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/merger/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:30:34+00:00"
---
## Merger class {#merger-class}

Represents `Merger` plugin.

```csharp
public sealed class Merger : IPlugin
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [Merger](merger/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.lowcode/merger/process/)(IPluginOptions) | Starts the `Merger` processing with the specified parameters. |

## Examples {#examples}

The example demonstrates how to merge two PDF documents.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### See Also {#see-also}

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)
