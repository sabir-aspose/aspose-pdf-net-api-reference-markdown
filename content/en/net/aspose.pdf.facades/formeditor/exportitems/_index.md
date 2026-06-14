---
title: "FormEditor.ExportItems"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor property. Sets options for combo box with export values"
type: docs
url: "/net/aspose.pdf.facades/formeditor/exportitems/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formeditor/exportitems/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:24+00:00"
---
## FormEditor.ExportItems property {#formeditorexportitems-property}

Sets options for combo box with export values.

```csharp
public string[][] ExportItems { get; set; }
```

## Examples {#examples}

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
formEditor.ExportItems = new string[][] 
{ 
    new string[] { "1", "Firs" }, 
    new string[] { "2", "Second" }, 
    new string[] { "3", "Third" } 
};
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### See Also {#see-also}

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
