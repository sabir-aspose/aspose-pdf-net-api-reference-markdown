---
title: "FormEditor.RenameField"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Change name of the field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/renamefield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/renamefield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:32+00:00"
---
## FormEditor.RenameField method {#formeditorrenamefield-method}

Change name of the field.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Old name of the field. |
| newFieldName | String | New name of the field. |

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
