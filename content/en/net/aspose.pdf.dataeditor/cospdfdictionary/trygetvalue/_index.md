---
title: "CosPdfDictionary.TryGetValue"
second_title: "Aspose.PDF for .NET API Reference"
description: "CosPdfDictionary method. For access to simple data type like string name bool number. Returns null for other types"
type: docs
url: "/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:09:17+00:00"
---
## CosPdfDictionary.TryGetValue method {#cospdfdictionarytrygetvalue-method}

For access to simple data type like string, name, bool, number. Returns null for other types.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key value |
| value | ICosPdfPrimitive& | returns [`ICosPdfPrimitive`](../../icospdfprimitive/) for key or null. |

### Return Value {#return-value}

Returns true if [`ICosPdfPrimitive`](../../icospdfprimitive/) is like string, name, bool, number. Returns false for all other types.

### See Also {#see-also}

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)
