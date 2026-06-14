---
title: "OutputIntents.Item"
second_title: "Aspose.PDF for .NET API Reference"
description: "OutputIntents property. Gets the output intent at the specified index"
type: docs
url: "/net/aspose.pdf/outputintents/item/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/outputintents/item/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:03:33+00:00"
---
## OutputIntents indexer {#outputintents-indexer}

Gets the output intent at the specified *index*.

```csharp
public OutputIntent this[int index] { get; }
```

| Parameter | Description |
| --- | --- |
| index | The zero-based index of the output intent to get. |

### Return Value {#return-value}

The output intent at the specified *index*.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* is less than 0 or *index* is equal to or greater than [`Count`](../count/). |
| InvalidOperationException | The document that contains the collection has no catalog to access the OutputIntents. |

### See Also {#see-also}

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
