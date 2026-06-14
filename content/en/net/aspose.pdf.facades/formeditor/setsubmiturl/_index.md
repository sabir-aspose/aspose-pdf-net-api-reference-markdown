---
title: "FormEditor.SetSubmitUrl"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Sets URL of the button"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setsubmiturl/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setsubmiturl/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:40+00:00"
---
## FormEditor.SetSubmitUrl method {#formeditorsetsubmiturl-method}

Sets URL of the button.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Submit button name. |
| url | String | Fully qualified URL. |

### Return Value {#return-value}

true if URL for button was successfully set.

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
