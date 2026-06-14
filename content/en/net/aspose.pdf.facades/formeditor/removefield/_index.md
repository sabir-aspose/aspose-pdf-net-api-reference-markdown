---
title: "FormEditor.RemoveField"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Remove field from the form"
type: docs
url: "/net/aspose.pdf.facades/formeditor/removefield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/removefield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:30+00:00"
---
## FormEditor.RemoveField method {#formeditorremovefield-method}

Remove field from the form.

```csharp
public void RemoveField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the field which must be removed. |

## Examples {#examples}

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
