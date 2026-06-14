---
title: "FormEditor.RemoveFieldAction"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Remove submit action of the field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/removefieldaction/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/removefieldaction/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:31+00:00"
---
## FormEditor.RemoveFieldAction method {#formeditorremovefieldaction-method}

Remove submit action of the field.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the field. |

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
