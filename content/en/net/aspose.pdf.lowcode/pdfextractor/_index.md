---
title: "Class PdfExtractor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.PdfExtractor class. Represents base functionality to extract text images and other types of content that may occur on the pages of PDF documents"
type: docs
url: "/net/aspose.pdf.lowcode/pdfextractor/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/pdfextractor/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:31:24+00:00"
---
## PdfExtractor class {#pdfextractor-class}

Represents base functionality to extract text, images, and other types of content that may occur on the pages of PDF documents.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.lowcode/pdfextractor/dispose/)() | Implementation of IDisposable. Actually, it is not necessary for PdfExtractor. |
| [Process](../../aspose.pdf.lowcode/pdfextractor/process/)(IPluginOptions) | Starts PdfExtractor processing with the specified parameters. |

## Remarks {#remarks}

The [`TextExtractor`](../textextractor/) object is used to extract text, or [`ImageExtractor`](../imageextractor/) to extract images.

## Examples {#examples}

The example demonstrates how to extract text content of PDF document.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### See Also {#see-also}

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)
