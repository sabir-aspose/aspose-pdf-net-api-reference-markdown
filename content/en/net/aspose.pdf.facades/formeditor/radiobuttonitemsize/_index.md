---
title: "FormEditor.RadioButtonItemSize"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor property. Gets or sets size of radio button item size when new radio button field is added"
type: docs
url: "/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:28+00:00"
---
## FormEditor.RadioButtonItemSize property {#formeditorradiobuttonitemsize-property}

Gets or sets size of radio button item size (when new radio button field is added).

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.RadioButtonItemSize = 20;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public double RadioButtonItemSize { get; set; }
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
