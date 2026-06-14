---
title: "OperatorCollection.Delete"
second_title: "Aspose.PDF for .NET API Reference"
description: "OperatorCollection method. Deletes operator from collection"
type: docs
url: "/net/aspose.pdf/operatorcollection/delete/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/operatorcollection/delete/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:02:05+00:00"
---
## Delete(int) {#delete_1}

Deletes operator from collection.

```csharp
public void Delete(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Index of operator which must be deleted. Operators numbering starts from 1. |

## Examples {#examples}

Example demonstrates how to delete operator by its index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### See Also {#see-also}

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Deletes operators from collection.

```csharp
public void Delete(Operator[] ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ops | Operator[] | Array of operators to delete |

## Examples {#examples-1}

Example demonstrates how to remove operator from page contents.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### See Also {#see-also-1}

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList<Operator>) {#delete_2}

Deletes operators from collection.

```csharp
public void Delete(IList<Operator> list)
```

| Parameter | Type | Description |
| --- | --- | --- |
| list | IList`1 | The list of operators to delete |

## Examples {#examples-2}

Example demonstrates how to remove operator from page contents.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### See Also {#see-also-2}

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
