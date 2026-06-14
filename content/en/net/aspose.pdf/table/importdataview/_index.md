---
title: "Table.ImportDataView"
second_title: "Aspose.PDF for .NET API Reference"
description: "Table method. Imports a DataView objects data into the table"
type: docs
url: "/net/aspose.pdf/table/importdataview/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/table/importdataview/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:09:19+00:00"
---
## Table.ImportDataView method {#tableimportdataview-method}

Imports a DataView object’s data into the table.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceDataView | DataView | The DataView object to be imported. |
| isColumnNamesImported | Boolean | Indicates whether the column names will be imported as first row. |
| firstFilledRow | Int32 | The zero based row number of the first cell in targer table from which import will start. If target table does not contain that row, it (and all previous if necessary) will be created |
| firstFilledColumn | Int32 | The zero based column number of the first cell in targer table from which import will start. The target table must contain that column before import starts, otherwise exception will be thrown. |
| maxRows | Int32 | Maximum amount of rows to be imported from source dataview. |
| maxColumns | Int32 | Maximum columns to be imported from source dataview. |

### See Also {#see-also}

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
