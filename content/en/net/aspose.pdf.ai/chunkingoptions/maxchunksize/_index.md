---
title: "ChunkingOptions.MaxChunkSize"
second_title: "Aspose.PDF for .NET API Reference"
description: "ChunkingOptions property. Gets or sets the maximum size of each chunk in tokens"
type: docs
url: "/net/aspose.pdf.ai/chunkingoptions/maxchunksize/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/chunkingoptions/maxchunksize/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:48:23+00:00"
---
## ChunkingOptions.MaxChunkSize property {#chunkingoptionsmaxchunksize-property}

Gets or sets the maximum size of each chunk in tokens.

```csharp
public int MaxChunkSize { get; set; }
```

### Property Value {#property-value}

The maximum chunk size in tokens. Must be between [`MinimumChunkSize`](../minimumchunksize/) and [`MaximumChunkSize`](../maximumchunksize/). Default is [`DefaultMaxChunkSize`](../defaultmaxchunksize/).

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when the value is less than [`MinimumChunkSize`](../minimumchunksize/) or greater than [`MaximumChunkSize`](../maximumchunksize/). |

### See Also {#see-also}

* class [ChunkingOptions](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
