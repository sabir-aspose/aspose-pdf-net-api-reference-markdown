---
title: "Timestamp.Process"
second_title: "Aspose.PDF for .NET API Reference"
description: "Timestamp method. Processes the timestamp plugin with the supplied options"
type: docs
url: "/net/aspose.pdf.lowcode/timestamp/process/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.lowcode/timestamp/process/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:33:02+00:00"
---
## Timestamp.Process method {#timestampprocess-method}

Processes the timestamp plugin with the supplied options.

```csharp
public ResultContainer Process(IPluginOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IPluginOptions | An options object containing inputs, outputs and timestamp settings. |

### Return Value {#return-value}

A [`ResultContainer`](../../resultcontainer/) with the operation results.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentNullException | If *options* is `null`. |
| InvalidOperationException | If *options* is not of type [`TimestampOptions`](../../timestampoptions/). |

### See Also {#see-also}

* class [ResultContainer](../../resultcontainer/)
* interface [IPluginOptions](../../ipluginoptions/)
* class [Timestamp](../)
* namespace [Aspose.Pdf.LowCode](../../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../../)
