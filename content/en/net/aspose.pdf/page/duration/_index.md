---
title: "Page.Duration"
second_title: "Aspose.PDF for .NET API Reference"
description: "Page property. Gets of set page display duration. This is time in seconds that page shall be displayed during presentation. Returns 1 if duration is not defined"
type: docs
url: "/net/aspose.pdf/page/duration/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/page/duration/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:03:52+00:00"
---
## Page.Duration property {#pageduration-property}

Gets of set page display duration. This is time in seconds that page shall be displayed during presentation. Returns -1 if duration is not defined.

```csharp
public double Duration { get; set; }
```

## Examples {#examples}

Example demonstrates how to get page duration

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### See Also {#see-also}

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
