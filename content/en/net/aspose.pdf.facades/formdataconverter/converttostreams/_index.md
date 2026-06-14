---
title: "FormDataConverter.ConvertToStreams"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormDataConverter method. Convert data in table into streams"
type: docs
url: "/net/aspose.pdf.facades/formdataconverter/converttostreams/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formdataconverter/converttostreams/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:09+00:00"
---
## FormDataConverter.ConvertToStreams method {#formdataconverterconverttostreams-method}

Convert data in table into streams.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destStream | Stream[] | Streams where data will be stored. |
| destType | DataType | Type of stored data. Valid values are: XML, FDF, XFDF. |

## Examples {#examples}

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
DataRow newrow = table.NewRow();
newrow["textField"] = "NEW DATA";
newrow["listboxField"] = "Item1";
newrow["comboboxField"] = "Item1";
newrow["checkboxField"] = "true";
newrow["radiobuttonField"] = "true";
table.Rows.Add(newrow);
fc.Table = table;
fc.ConvertToStreams(new Stream[] { stream }, DataType.XML);
```

### See Also {#see-also}

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
