---
title: "Class Splitter"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Splitter class. Represents Splitter plugin"
type: docs
url: "/net/aspose.pdf.lowcode/splitter/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/splitter/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:32:14+00:00"
---
## Splitter class {#splitter-class}

Represents `Splitter` plugin.

```csharp
public class Splitter : IPlugin
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [Splitter](splitter/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.lowcode/splitter/process/)(IPluginOptions) | Starts the `Splitter` processing with the specified parameters. |

## Examples {#examples}

The example demonstrates how to split PDF document.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### See Also {#see-also}

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)
