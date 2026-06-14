---
title: "Class Signature"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Signature class. Represents Signature plugin"
type: docs
url: "/net/aspose.pdf.lowcode/signature/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/signature/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:32:04+00:00"
---
## Signature class {#signature-class}

Represents `Signature` plugin.

```csharp
public sealed class Signature : IPlugin
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [Signature](signature/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.lowcode/signature/process/)(IPluginOptions) | Starts the `Signature` processing with the specified parameters. |

## Examples {#examples}

The example demonstrates how to sign PDF document.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### See Also {#see-also}

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)
