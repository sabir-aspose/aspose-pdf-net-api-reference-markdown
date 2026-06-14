---
title: "FormDataConverter.ExportFromDataBase"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormDataConverter method. Exports data from database into table"
type: docs
url: "/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:12+00:00"
---
## FormDataConverter.ExportFromDataBase method {#formdataconverterexportfromdatabase-method}

Exports data from database into table.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connectString | String | Connection string for database. |
| dbType | DataType | Connection type: OLEDB or ODBC. |

## Examples {#examples}

```csharp
FormDataConverter fc = new FormDataConverter();
string connection = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=ConverterDatabase.mdb";
DataTable table = new DataTable();
table.TableName = "TestSource";
table.Columns.Add("TEXT_VALUE");
table.Columns.Add("INT_VALUE");
fc.Table = table;
fc.ExportFromDataBase(connection, DataType.OLEDB);
```

### See Also {#see-also}

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
