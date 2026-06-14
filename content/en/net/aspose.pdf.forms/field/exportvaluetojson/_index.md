---
title: "Field.ExportValueToJson"
second_title: "Aspose.PDF for .NET API Reference"
description: "Field method. Exports the content of the specified field into a JSON stream. Button field value are not exported"
type: docs
url: "/net/aspose.pdf.forms/field/exportvaluetojson/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.forms/field/exportvaluetojson/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:21:17+00:00"
---
## Field.ExportValueToJson method {#fieldexportvaluetojson-method}

Exports the content of the specified field into a JSON stream. Button field value are not exported.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputJsonStream | Stream | The output JSON stream where the field data will be written. |
| indented | Boolean | Optional. Specifies whether the JSON output should be indented for better readability. The default value is true. |

## Examples {#examples}

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### See Also {#see-also}

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)
