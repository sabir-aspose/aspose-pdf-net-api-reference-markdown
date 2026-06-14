---
title: "Form.GetRichText"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Get a Rich Text fields value including the formattinf information of every character"
type: docs
url: "/net/aspose.pdf.facades/form/getrichtext/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getrichtext/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:52+00:00"
---
## Form.GetRichText method {#formgetrichtext-method}

Get a Rich Text field’s value, including the formattinf information of every character.

```csharp
public string GetRichText(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name of the Rich Text field. |

### Return Value {#return-value}

Return a string containing formatting information of the Rich Text field.

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
