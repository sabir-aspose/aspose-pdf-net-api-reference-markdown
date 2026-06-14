---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns the current value for radio button option fields"
type: docs
url: "/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:46+00:00"
---
## Form.GetButtonOptionCurrentValue method {#formgetbuttonoptioncurrentvalue-method}

Returns the current value for radio button option fields.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field Name |

### Return Value {#return-value}

String value for the current radio group optino. See also [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
