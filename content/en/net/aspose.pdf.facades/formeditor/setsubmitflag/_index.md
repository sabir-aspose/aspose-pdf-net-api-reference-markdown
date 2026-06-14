---
title: "FormEditor.SetSubmitFlag"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Set submit flag of submit button"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setsubmitflag/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setsubmitflag/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:39+00:00"
---
## FormEditor.SetSubmitFlag method {#formeditorsetsubmitflag-method}

Set submit flag of submit button.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of submit button. |
| submitFormFlag | SubmitFormFlag | Submit flag. |

### Return Value {#return-value}

true if field was found and submit flag was successfully set.

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### See Also {#see-also}

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
