---
title: "PdfXmpMetadata.Contains"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Checks if dictionary contains the specified key"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/contains/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/contains/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:14+00:00"
---
## Contains(string) {#contains_2}

Checks if dictionary contains the specified key.

```csharp
public bool Contains(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key which will be checked. |

### Return Value {#return-value}

True - if the dictionary contains the specified key; otherwise, false.

## Examples {#examples}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### See Also {#see-also}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Checks if dictionary contains the specified property.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | DefaultMetadataProperties | Property which will be checked. |

### Return Value {#return-value-1}

True - if the dictionary contains the specified property; otherwise, false.

### See Also {#see-also-1}

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair<string, XmpValue>) {#contains_1}

Checks does specified key-value pair is contained in the dictionary.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Key-value pair. |

### Return Value {#return-value-2}

true if this pauir was found.

### See Also {#see-also-2}

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
