---
title: "FormEditor.Single2Multiple"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Change a singlelined text field to a multiplelined one"
type: docs
url: "/net/aspose.pdf.facades/formeditor/single2multiple/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/single2multiple/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:41+00:00"
---
## FormEditor.Single2Multiple method {#formeditorsingle2multiple-method}

Change a single-lined text field to a multiple-lined one.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |

### Return Value {#return-value}

If success, return true;else false.

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
