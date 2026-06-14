---
title: "Class InterruptMonitor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Multithreading.InterruptMonitor class. Represents information about interruption"
type: docs
url: "/net/aspose.pdf.multithreading/interruptmonitor/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.multithreading/interruptmonitor/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:33:20+00:00"
---
## InterruptMonitor class {#interruptmonitor-class}

Represents information about interruption.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | The default constructor. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Monitor’s cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Gets or sets the IInterruptMonitor instance which is unique for each thread. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Disposes used resources. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Sends a request to interrupt operations. |

### See Also {#see-also}

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)
