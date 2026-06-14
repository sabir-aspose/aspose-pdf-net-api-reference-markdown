---
title: "FormEditor.SetFieldLimit"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Sets maximum character count of the text field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setfieldlimit/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setfieldlimit/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:38+00:00"
---
## FormEditor.SetFieldLimit method {#formeditorsetfieldlimit-method}

Sets maximum character count of the text field.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the text field. |
| fieldLimit | Int32 | New value of limit for the field. |

### Return Value {#return-value}

true if field limit was successfully set.

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
