---
title: "ChunkingOptions.OverlapSize"
second_title: "Aspose.PDF for .NET API Reference"
description: "ChunkingOptions property. Gets or sets the number of tokens to overlap between consecutive chunks"
type: docs
url: "/net/aspose.pdf.ai/chunkingoptions/overlapsize/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/chunkingoptions/overlapsize/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:48:25+00:00"
---
## ChunkingOptions.OverlapSize property {#chunkingoptionsoverlapsize-property}

Gets or sets the number of tokens to overlap between consecutive chunks.

```csharp
public int OverlapSize { get; set; }
```

### Property Value {#property-value}

The overlap size in tokens. Must be non-negative and less than [`MaxChunkSize`](../maxchunksize/). Default is [`DefaultOverlapSize`](../defaultoverlapsize/).

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when the value is negative. |

### See Also {#see-also}

* class [ChunkingOptions](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
