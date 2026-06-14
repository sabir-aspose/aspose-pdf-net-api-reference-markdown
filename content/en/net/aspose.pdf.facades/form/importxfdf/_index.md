---
title: "Form.ImportXfdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Imports the content of the fields from the xfdfxml file and put them into the new pdf"
type: docs
url: "/net/aspose.pdf.facades/form/importxfdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/importxfdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:56+00:00"
---
## Form.ImportXfdf method {#formimportxfdf-method}

Imports the content of the fields from the xfdf(xml) file and put them into the new pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXfdfStream | Stream | The input xfdf(xml) stream. |

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
