---
title: "Form.GetFieldType"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns type of field"
type: docs
url: "/net/aspose.pdf.facades/form/getfieldtype/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getfieldtype/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:51+00:00"
---
## Form.GetFieldType method {#formgetfieldtype-method}

Returns type of field.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field name. |

### Return Value {#return-value}

Element of FileType enumeration corresponding to field type.

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### See Also {#see-also}

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
