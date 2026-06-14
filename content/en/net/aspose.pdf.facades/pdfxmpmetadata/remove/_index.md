---
title: "PdfXmpMetadata.Remove"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Removes element with specified key"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/remove/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/remove/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:25+00:00"
---
## Remove(DefaultMetadataProperties) {#remove_2}

Removes element with specified key.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | Key of the element which will be deleted. |

## Examples {#examples}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### See Also {#see-also}

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Removes key from the dictionary.

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key which will be removed. |

### Return Value {#return-value}

True - if key removed; otherwise, false.

## Examples {#examples-1}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### See Also {#see-also-1}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair<string, XmpValue>) {#remove}

Removes key/value pair from the collection.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Key/value pair to be removed. |

### Return Value {#return-value-1}

true if pair was found and removed.

### See Also {#see-also-2}

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
