---
title: "FormEditor.CopyOuterField"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Copies an existing field from one PDF document to another document with original page number and ordinates. Notice Only for AcroForm fields excluding radio box"
type: docs
url: "/net/aspose.pdf.facades/formeditor/copyouterfield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/copyouterfield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:21+00:00"
---
## CopyOuterField(string, string) {#copyouterfield}

Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The name of PDF document which containes the field to be copied. |
| fieldName | String | The original fully qualified field name. |

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The name of PDF document which containes the field to be copied. |
| fieldName | String | The original fully qualified field name. |
| pageNum | Int32 | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |

## Examples {#examples-1}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### See Also {#see-also-1}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The name of PDF document which containes the field to be copied. |
| fieldName | String | The original fully qualified field name. |
| pageNum | Int32 | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | Single | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | Single | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

## Examples {#examples-2}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### See Also {#see-also-2}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
