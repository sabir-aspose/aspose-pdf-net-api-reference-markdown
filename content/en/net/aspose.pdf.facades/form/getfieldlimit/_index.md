---
title: "Form.GetFieldLimit"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Get the limitation of text field"
type: docs
url: "/net/aspose.pdf.facades/form/getfieldlimit/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getfieldlimit/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:50+00:00"
---
## Form.GetFieldLimit method {#formgetfieldlimit-method}

Get the limitation of text field.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |

### Return Value {#return-value}

Return the limitation number of characters a text field can be filled. It not set, return 0.

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
