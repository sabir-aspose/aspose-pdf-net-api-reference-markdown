---
title: "Form.GetFullFieldName"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Gets the full field name according to its short field name"
type: docs
url: "/net/aspose.pdf.facades/form/getfullfieldname/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getfullfieldname/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:51+00:00"
---
## Form.GetFullFieldName method {#formgetfullfieldname-method}

Gets the full field name according to its short field name.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |

### Return Value {#return-value}

The full field name.

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
