---
title: "FormDataConverter.ImportIntoDataBase"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormDataConverter method. Imports data from table into database"
type: docs
url: "/net/aspose.pdf.facades/formdataconverter/importintodatabase/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formdataconverter/importintodatabase/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:13+00:00"
---
## FormDataConverter.ImportIntoDataBase method {#formdataconverterimportintodatabase-method}

Imports data from table into database.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connectString | String | Connection string of database. |
| dbType | DataType | Type of database connection: OLEDB or ODBC. |

## Examples {#examples}

```csharp
FormDataConverter fc = new FormDataConverter();
DataTable table = new DataTable();
table.TableName = "test";
table.Columns.Add("TEXT_VALUE");
table.Columns.Add("INT_VALUE");
fc.Table = table;
DataRow row = table.NewRow();
row["TEXT_VALUE"] = "AAA";
row["INT_VALUE"] = "123";
table.Rows.Add(row);
string connection = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=ConverterDatabase.mdb";
fc.ImportIntoDataBase(connection, DataType.OLEDB);
```

### See Also {#see-also}

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
