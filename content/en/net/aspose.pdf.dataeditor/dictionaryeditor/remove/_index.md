---
title: "DictionaryEditor.Remove"
second_title: "Aspose.PDF for .NET API Reference"
description: "DictionaryEditor method. Removes the element with the specified key from the DictionaryEditor"
type: docs
url: "/net/aspose.pdf.dataeditor/dictionaryeditor/remove/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.dataeditor/dictionaryeditor/remove/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:09:47+00:00"
---
## Remove(string) {#remove_1}

Removes the element with the specified key from the [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | The key of the element to remove. |

### Return Value {#return-value}

True if the element is successfully removed; otherwise, false. This method also returns false if key was not found in the original dictionary or key the key is not editable

### See Also {#see-also}

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair<string, ICosPdfPrimitive>) {#remove}

Removes the first occurrence of a specific object from the [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | The object to remove from the [`DictionaryEditor`](../). |

### Return Value {#return-value-1}

true if item was successfully removed from the [`DictionaryEditor`](../); otherwise, false. This method also returns false if item is not found in the original [`DictionaryEditor`](../).

### See Also {#see-also-1}

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)
