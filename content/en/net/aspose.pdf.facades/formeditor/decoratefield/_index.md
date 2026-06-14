---
title: "FormEditor.DecorateField"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Changes visual attributes of the specified field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/decoratefield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/decoratefield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:22+00:00"
---
## DecorateField(string) {#decoratefield_2}

Changes visual attributes of the specified field.

```csharp
public void DecorateField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |

## Examples {#examples}

```csharp
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

Changes visual attributes of all fields with the specified field type.

```csharp
public void DecorateField(FieldType fieldType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Type of fields which will be decorated. |

## Examples {#examples-1}

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//decorate all text fields.
fe.DecorateField(FieldType.Text);
```

### See Also {#see-also-1}

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

Changes visual attributes of all fields in the PDF document.

```csharp
public void DecorateField()
```

## Examples {#examples-2}

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//decorate all fields.
fe.DecorateField();
```

### See Also {#see-also-2}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
