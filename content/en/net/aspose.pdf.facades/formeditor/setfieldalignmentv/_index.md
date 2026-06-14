---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Set the vertical alignment style of a text field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setfieldalignmentv/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setfieldalignmentv/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:35+00:00"
---
## FormEditor.SetFieldAlignmentV method {#formeditorsetfieldalignmentv-method}

Set the vertical alignment style of a text field.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |
| alignment | Int32 | The alignment style definition, including FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle and FormFieldFacade.AlignRight. |

### Return Value {#return-value}

true if field was found and alignment was successfully filled.

## Examples {#examples}

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
