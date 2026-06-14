---
title: "OperatorCollection.Item"
second_title: "Aspose.PDF for .NET API Reference"
description: "OperatorCollection property. Gets operator by its index"
type: docs
url: "/net/aspose.pdf/operatorcollection/item/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/operatorcollection/item/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:02:10+00:00"
---
## OperatorCollection indexer {#operatorcollection-indexer}

Gets operator by its index.

```csharp
public override Operator this[int index] { get; set; }
```

| Parameter | Description |
| --- | --- |
| index | Index of operator. Numbering is starts from 1. |

### Return Value {#return-value}

Operator from requested index

## Examples {#examples}

Example demonstrates how to get operator of page contents by index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### See Also {#see-also}

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
