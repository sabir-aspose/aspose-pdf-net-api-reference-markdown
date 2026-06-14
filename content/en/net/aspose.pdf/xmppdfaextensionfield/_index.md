---
title: "Class XmpPdfAExtensionField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XmpPdfAExtensionField class. This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema but defines a field in a structure instead of a property. Schema namespace URI http//www.aiim.org/pdfa/ns/field Required schema namespace prefix pdfaField"
type: docs
url: "/net/aspose.pdf/xmppdfaextensionfield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/xmppdfaextensionfield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:11:59+00:00"
---
## XmpPdfAExtensionField class {#xmppdfaextensionfield-class}

This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema namespace URI: [http://www.aiim.org/pdfa/ns/field#](http://www.aiim.org/pdfa/ns/field#) Required schema namespace prefix: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | Initializes object. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Gets the description. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | Field name. Field names must be valid XML element names. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Gets or sets the value. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. Predefined XMP type names or names of custom types. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | Returns the list of xml elements that represent field in xml tree. |

### See Also {#see-also}

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
