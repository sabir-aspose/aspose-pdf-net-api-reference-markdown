---
title: "FormEditor.SetFieldAlignment"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Set the alignment style of a text field"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setfieldalignment/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setfieldalignment/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:34+00:00"
---
## FormEditor.SetFieldAlignment method {#formeditorsetfieldalignment-method}

Set the alignment style of a text field.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |
| alignment | Int32 | The alignment style definition, including FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter and FormFieldFacade.AlignRight. |

### Return Value {#return-value}

true if true if field was found and alignment was set.

## Examples {#examples}

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
