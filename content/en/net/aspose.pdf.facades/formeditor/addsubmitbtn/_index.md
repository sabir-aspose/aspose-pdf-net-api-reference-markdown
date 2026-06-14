---
title: "FormEditor.AddSubmitBtn"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Add submit button on the form"
type: docs
url: "/net/aspose.pdf.facades/formeditor/addsubmitbtn/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/addsubmitbtn/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:19+00:00"
---
## FormEditor.AddSubmitBtn method {#formeditoraddsubmitbtn-method}

Add submit button on the form.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of new button. |
| page | Int32 | Page where button will be placed. |
| label | String | Button caption. |
| url | String | URL of the submit button. |
| llx | Single | Abscissa of the lower-left corner. |
| lly | Single | Ordinate of the lower-left corner. |
| urx | Single | Abscissa of the upper-right corner. |
| ury | Single | Ordinate of the upper-right corner. |

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
