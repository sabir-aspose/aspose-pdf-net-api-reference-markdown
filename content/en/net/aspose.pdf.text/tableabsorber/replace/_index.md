---
title: "TableAbsorber.Replace"
second_title: "Aspose.PDF for .NET API Reference"
description: "TableAbsorber method. Replaces an AbsorbedTable with Table on the page"
type: docs
url: "/net/aspose.pdf.text/tableabsorber/replace/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/tableabsorber/replace/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:44:40+00:00"
---
## TableAbsorber.Replace method {#tableabsorberreplace-method}

Replaces an [`AbsorbedTable`](../../absorbedtable/) with [`Table`](../../../aspose.pdf/table/) on the page.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | Pdf pocument page object. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) to be replaced. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) to replace old table. |

## Remarks {#remarks}

Please take into account it changes TableList collection. In case removing/replacing tables in loop please use copy of TableList collection.

### See Also {#see-also}

* class [Page](../../../aspose.pdf/page/)
* class [AbsorbedTable](../../absorbedtable/)
* class [Table](../../../aspose.pdf/table/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
