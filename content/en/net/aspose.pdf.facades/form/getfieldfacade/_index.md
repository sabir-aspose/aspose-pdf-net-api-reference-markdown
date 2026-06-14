---
title: "Form.GetFieldFacade"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns FrofmFieldFacade object containing all appearance attributes"
type: docs
url: "/net/aspose.pdf.facades/form/getfieldfacade/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getfieldfacade/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:48+00:00"
---
## Form.GetFieldFacade method {#formgetfieldfacade-method}

Returns FrofmFieldFacade object containing all appearance attributes.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field to read. |

### Return Value {#return-value}

FormFieldFacade object

### See Also {#see-also}

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
