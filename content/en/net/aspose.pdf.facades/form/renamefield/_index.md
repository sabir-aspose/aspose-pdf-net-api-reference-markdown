---
title: "Form.RenameField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Renames a field. Either AcroForm field or XFA field is OK"
type: docs
url: "/net/aspose.pdf.facades/form/renamefield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/renamefield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:58+00:00"
---
## Form.RenameField method {#formrenamefield-method}

Renames a field. Either AcroForm field or XFA field is OK.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | the old field name |
| newFieldName | String | the new field name |

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
