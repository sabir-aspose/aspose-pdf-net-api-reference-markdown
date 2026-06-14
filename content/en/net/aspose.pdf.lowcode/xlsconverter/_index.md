---
title: "Class XlsConverter"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.XlsConverter class. Represents XlsConverter plugin"
type: docs
url: "/net/aspose.pdf.lowcode/xlsconverter/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/xlsconverter/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:33:16+00:00"
---
## XlsConverter class {#xlsconverter-class}

Represents `XlsConverter` plugin.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [XlsConverter](xlsconverter/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.lowcode/xlsconverter/dispose/)() | Implementation of IDisposable. |
| [Process](../../aspose.pdf.lowcode/xlsconverter/process/)(IPluginOptions) | Starts the PdfToExcel processing with the specified parameters. |

## Examples {#examples}

The example demonstrates how to convert PDF to XLSX document.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### See Also {#see-also}

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)
