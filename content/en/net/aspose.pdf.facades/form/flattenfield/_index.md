---
title: "Form.FlattenField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid all the fields will remain unchangable"
type: docs
url: "/net/aspose.pdf.facades/form/flattenfield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/flattenfield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:44+00:00"
---
## Form.FlattenField method {#formflattenfield-method}

Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid, all the fields will remain unchangable.

```csharp
public void FlattenField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The name of the field to be flattened. |

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
