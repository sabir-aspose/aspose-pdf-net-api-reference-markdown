---
title: "Form.ExportXfdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Exports the content of the fields of the pdf into the xml stream. The button fields value will not be exported"
type: docs
url: "/net/aspose.pdf.facades/form/exportxfdf/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/exportxfdf/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:37+00:00"
---
## Form.ExportXfdf method {#formexportxfdf-method}

Exports the content of the fields of the pdf into the xml stream. The button field’s value will not be exported.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputXfdfStream | Stream | The output xml stream. |

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
