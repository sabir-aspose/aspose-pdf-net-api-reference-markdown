---
title: "Interface IInterruptMonitor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Multithreading.IInterruptMonitor interface. Represents information about interruption"
type: docs
url: "/net/aspose.pdf.multithreading/iinterruptmonitor/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.multithreading/iinterruptmonitor/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:33:18+00:00"
---
## IInterruptMonitor interface {#iinterruptmonitor-interface}

Represents information about interruption.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Monitor’s cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Sends a request to interrupt operations. |

### See Also {#see-also}

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)
