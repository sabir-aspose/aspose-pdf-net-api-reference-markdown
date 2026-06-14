---
title: "FormEditor.RadioHoriz"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor property. The flag to indicate whether the radios are arranged horizontally or vertically default value is true"
type: docs
url: "/net/aspose.pdf.facades/formeditor/radiohoriz/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/radiohoriz/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:29+00:00"
---
## FormEditor.RadioHoriz property {#formeditorradiohoriz-property}

The flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

```csharp
public bool RadioHoriz { get; set; }
```

## Examples {#examples}

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
