---
title: "Table.ImportArray"
second_title: "Aspose.PDF for .NET API Reference"
description: "Table method. Imports onedimensional array of data into table. Import goes one cell per each arrays item and starts from row and column defined in parameters. During import if detected that necessary rows are still absenti.e. target table is too small to absorb all data necessary rows will be created"
type: docs
url: "/net/aspose.pdf/table/importarray/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/table/importarray/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:09:18+00:00"
---
## Table.ImportArray method {#tableimportarray-method}

Imports one-dimensional array of data into table. Import goes one cell per each array’s item and starts from row and column defined in parameters. During import, if detected that necessary rows are still absent(i.e. target table is too small to absorb all data), necessary rows will be created

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parameter | Type | Description |
| --- | --- | --- |
| importedArray | Object[] | imported data, nulls will be imported as empty strings |
| firstFilledRow | Int32 | define number of first target row in target table from wich import will start. If amount of rows in target table less then required, missing rows will be created first. |
| firstFilledColumn | Int32 | specifies number of first target column in target table , column must be present in target table before start of import |
| isLeftColumnsFilled | Boolean | If ‘isLeftColumnsFilled’=false, then in second and all subsequent filled rows cells that are on the left hand from firstFilledColumn will be skipped |

### See Also {#see-also}

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
