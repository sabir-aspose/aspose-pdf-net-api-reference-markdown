---
title: "Form.ExportXml"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Exports the content of the fields of the pdf into the xml stream. The button fields value will not be exported"
type: docs
url: "/net/aspose.pdf.facades/form/exportxml/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/exportxml/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:38+00:00"
---
## Form.ExportXml method {#formexportxml-method}

Exports the content of the fields of the pdf into the xml stream. The button field’s value will not be exported.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputXmlStream | Stream | Output Xml stream. |

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
