---
title: "Form.FieldNames"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form property. Gets list of field names on the form"
type: docs
url: "/net/aspose.pdf.facades/form/fieldnames/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/fieldnames/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:39+00:00"
---
## Form.FieldNames property {#formfieldnames-property}

Gets list of field names on the form.

```csharp
public string[] FieldNames { get; }
```

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
