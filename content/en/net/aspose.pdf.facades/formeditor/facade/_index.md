---
title: "FormEditor.Facade"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor property. Sets visual attributes of the field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/facade/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/facade/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:24+00:00"
---
## FormEditor.Facade property {#formeditorfacade-property}

Sets visual attributes of the field.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Examples {#examples}

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
fe.Save();
```

### See Also {#see-also}

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
