---
title: "PdfXmpMetadata.Add"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Adds value to XMP metadata"
type: docs
url: "/net/aspose.pdf.facades/pdfxmpmetadata/add/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdfxmpmetadata/add/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:12+00:00"
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Adds value to XMP metadata.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | The key name. |
| value | XmpValue | Value which will be added. |

## Examples {#examples}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### See Also {#see-also}

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Adds extension field into metadata.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | The pdf extension object to add. |
| namespacePrefix | String | The prefix of schema. |
| namespaceUri | String | The namespace uri of schema. |
| schemaDescription | String | The optional description of schema. |

### See Also {#see-also-1}

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Adds new element to the dictionary object.

```csharp
public void Add(string key, XmpValue value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key of new element. |
| value | XmpValue | Value of the element. |

## Examples {#examples-1}

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### See Also {#see-also-2}

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Adds new element to the dictionary object.

```csharp
public void Add(string key, object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key of new element. |
| value | Object | Value of the element. |

### See Also {#see-also-3}

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair<string, XmpValue>) {#add_2}

Adds pair with key and value into the dictionary.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Item to be added. |

### See Also {#see-also-4}

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
