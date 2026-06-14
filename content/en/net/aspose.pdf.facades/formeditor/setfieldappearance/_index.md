---
title: "FormEditor.SetFieldAppearance"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Set field flags"
type: docs
url: "/net/aspose.pdf.facades/formeditor/setfieldappearance/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/setfieldappearance/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:36+00:00"
---
## FormEditor.SetFieldAppearance method {#formeditorsetfieldappearance-method}

Set field flags

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field whose flags should be updated. |
| flags | AnnotationFlags | Flag of the field. |

### Return Value {#return-value}

true if flags were updated successfully.

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### See Also {#see-also}

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
