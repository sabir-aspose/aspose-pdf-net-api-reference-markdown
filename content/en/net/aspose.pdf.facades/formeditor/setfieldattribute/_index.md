---
title: "FormEditor.SetFieldAttribute"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Set attributes of field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setfieldattribute/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setfieldattribute/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:36+00:00"
---
## FormEditor.SetFieldAttribute method {#formeditorsetfieldattribute-method}

Set attributes of field.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field which attributes should be set. |
| flag | PropertyFlag | Flag (NoExport/ReadOnly/Required) |

### Return Value {#return-value}

true if attribute was set successfully.

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### See Also {#see-also}

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
