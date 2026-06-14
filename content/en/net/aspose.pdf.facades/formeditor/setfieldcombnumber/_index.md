---
title: "FormEditor.SetFieldCombNumber"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Sets number of combs for a regular singleline text field the field is automatically divided into as many equally spaced positions or combs as the value of combNumber parameter"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setfieldcombnumber/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setfieldcombnumber/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:37+00:00"
---
## FormEditor.SetFieldCombNumber method {#formeditorsetfieldcombnumber-method}

Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |
| combNumber | Int32 | The number of combs to divide the field into. |

### Return Value {#return-value}

If success, return true;else false.

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
