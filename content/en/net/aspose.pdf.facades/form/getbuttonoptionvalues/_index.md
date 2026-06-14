---
title: "Form.GetButtonOptionValues"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups"
type: docs
url: "/net/aspose.pdf.facades/form/getbuttonoptionvalues/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getbuttonoptionvalues/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:47+00:00"
---
## Form.GetButtonOptionValues method {#formgetbuttonoptionvalues-method}

Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field Name |

### Return Value {#return-value}

Hash table of option values keyed by form item name

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
