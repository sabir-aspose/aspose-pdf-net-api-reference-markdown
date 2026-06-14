---
title: "Class OpenAIImageDescriptionCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAIImageDescriptionCopilot class. Provides image processing functionality for OpenAICopilot class. Example usage of creating an OpenAI client configuration of ImageDescriptionCopilot options and usage of the copilot to generate image descriptions and add descriptions to attached documents"
type: docs
url: "/net/aspose.pdf.ai/openaiimagedescriptioncopilot/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/openaiimagedescriptioncopilot/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:54:23+00:00"
---
## OpenAIImageDescriptionCopilot class {#openaiimagedescriptioncopilot-class}

Provides image processing functionality for OpenAICopilot class. Example usage of creating an OpenAI client, configuration of ImageDescriptionCopilot options, and usage of the copilot to generate image descriptions and add descriptions to attached documents.

```csharp
// Create AI client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Create copilot options.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument(new PdfDocument // Attach documents.
    {
        Name = "Another_Pdf_with_images",
        Document = new Document(GetInputPath("Pdf_with_images_low_res_bw.pdf"))
    })
    .WithDocument(GetInputPath("Mona_liza.jpg")) // Attach images
    .WithDocument(GetInputPath("Pdf_with_images.pdf")); // Attach document paths.

// Create copilot.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Get Image descriptions.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Use extension method to add image descriptions to attached documents.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>) | Initializes a new instance of the `OpenAIImageDescriptionCopilot` class. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### See Also {#see-also}

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)
