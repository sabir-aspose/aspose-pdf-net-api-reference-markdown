---
title: "Class CompletionResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.CompletionResponse class. Represents a chat completion response returned by model based on the provided input"
type: docs
url: "/net/aspose.pdf.ai/completionresponse/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/completionresponse/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:48:46+00:00"
---
## CompletionResponse class {#completionresponse-class}

Represents a chat completion response returned by model, based on the provided input.

```csharp
public class CompletionResponse : BaseResponse
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [CompletionResponse](completionresponse/)() | The default constructor. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Gets or sets a list of chat completion choices. Can be more than one if n is greater than 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Gets or sets the Unix timestamp (in seconds) of when the chat completion was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Gets or sets a unique identifier for the chat completion. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Gets or sets the model used for the chat completion. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Gets or sets the object type, which is always chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Gets or sets the fingerprint that represents the backend configuration that the model runs with. Can be used in conjunction with the seed request parameter to understand when backend changes have been made that might impact determinism. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Gets or sets the usage statistics for the completion request. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Returns the content of the first choice as a string. |

### See Also {#see-also}

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)
