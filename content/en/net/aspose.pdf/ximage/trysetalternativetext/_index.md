---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF for .NET API Reference"
description: "XImage method. Sets alternative text for an XImage on the page"
type: docs
url: "/net/aspose.pdf/ximage/trysetalternativetext/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/ximage/trysetalternativetext/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:11:26+00:00"
---
## XImage.TrySetAlternativeText method {#ximagetrysetalternativetext-method}

Sets alternative text for an XImage on the page.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alternativeText | String | The alternative text to be specified. |
| page | Page | Page where XImage is located. |

### Return Value {#return-value}

True if alternativeText for XImage is set. False if alternativeText for XImage not set.

## Remarks {#remarks}

The method returns false in the following cases: - The XImage is not found on the specified page. - The XImage appears multiple times on the page with different structural elements, making it ambiguous which instance should receive the alternative text.

### See Also {#see-also}

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
