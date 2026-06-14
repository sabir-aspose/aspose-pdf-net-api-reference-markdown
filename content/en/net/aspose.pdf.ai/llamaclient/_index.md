---
title: "Class LlamaClient"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.LlamaClient class. Represents a client for interacting with the Llama API"
type: docs
url: "/net/aspose.pdf.ai/llamaclient/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/llamaclient/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:52:20+00:00"
---
## LlamaClient class {#llamaclient-class}

Represents a client for interacting with the Llama API.

Represents a client for interacting with the Llama API.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Gets or sets the backoff delay in seconds. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Gets or sets the maximum number of HTTP request retries. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Gets or sets the polling interval in seconds. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Gets or sets the polling timeout in seconds. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Creates a chat completion request in the Llama service. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Disposes of the resources used by the [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions<LlamaSummaryCopilotOptions>) | Gets an instance of [`ISummaryCopilot`](../isummarycopilot/) with the specified options. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Creates a new instance of [`Builder`](../llamaclient.builder/) with the provided API key. |

## Other Members {#other-members}

| Name | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Builder class for creating an instance of `LlamaClient`. |

### See Also {#see-also}

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient<TOptions>](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)
