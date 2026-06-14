---
title: "Form.GetField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Gets the fields value according to its field name"
type: docs
url: "/net/aspose.pdf.facades/form/getfield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getfield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:47+00:00"
---
## Form.GetField method {#formgetfield-method}

Gets the field’s value according to its field name.

```csharp
public string GetField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |

### Return Value {#return-value}

The field’s value.

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
