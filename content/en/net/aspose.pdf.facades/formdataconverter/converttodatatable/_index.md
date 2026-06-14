---
title: "FormDataConverter.ConvertToDataTable"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormDataConverter method. Convert files of strems into table"
type: docs
url: "/net/aspose.pdf.facades/formdataconverter/converttodatatable/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formdataconverter/converttodatatable/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:08+00:00"
---
## FormDataConverter.ConvertToDataTable method {#formdataconverterconverttodatatable-method}

Convert files of strems into table.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreams | Stream[] | Array of source streams in specified format. |
| sourceType | DataType | Format of data in streams. Valid values are: PDF, FDF, XFDF, XML. |

## Examples {#examples}

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
FormDataConverter fc = new FormDataConverter();
Stream stream = new FileStream("PdfWithAcroForm.pdf", FileMode.Open);
fc.Table = table;
fc.ConvertToDataTable(new Stream[] { stream }, DataType.PDF);
stream.Close();
```

### See Also {#see-also}

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
