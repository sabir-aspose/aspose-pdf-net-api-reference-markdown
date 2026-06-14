---
title: "Form.GetFieldFlag"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns flags of the field"
type: docs
url: "/net/aspose.pdf.facades/form/getfieldflag/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getfieldflag/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:49+00:00"
---
## Form.GetFieldFlag method {#formgetfieldflag-method}

Returns flags of the field.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field name |

### Return Value {#return-value}

Property flag (ReadOnly/ Required/NoExport

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### See Also {#see-also}

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
