---
title: "OutputIntents.CopyTo"
second_title: "Aspose.PDF for .NET API Reference"
description: "OutputIntents method. Copies the elements of the collection to the arraystarting at the particular arrayIndex into the array"
type: docs
url: "/net/aspose.pdf/outputintents/copyto/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/outputintents/copyto/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:03:30+00:00"
---
## OutputIntents.CopyTo method {#outputintentscopyto-method}

Copies the elements of the collection to the *array*,starting at the particular *arrayIndex* into the array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| array | OutputIntent[] | The one-dimensional array that is the destination of the output intents copied from the collection. The array must have zero-based indexing. |
| arrayIndex | Int32 | The zero-based index in *array* at which copying begins. |

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentNullException | *array* is null. |
| ArgumentOutOfRangeException | *arrayIndex* is less than 0. |
| ArgumentException | The number of elements in the source [`OutputIntents`](../) is greater than the available space from *arrayIndex* to the end of the destination *array*. |

### See Also {#see-also}

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
