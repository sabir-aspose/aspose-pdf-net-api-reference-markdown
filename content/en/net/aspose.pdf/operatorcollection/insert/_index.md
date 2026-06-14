---
title: "OperatorCollection.Insert"
second_title: "Aspose.PDF for .NET API Reference"
description: "OperatorCollection method. Inserts operator into collection"
type: docs
url: "/net/aspose.pdf/operatorcollection/insert/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/operatorcollection/insert/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:02:07+00:00"
---
## Insert(int, Operator) {#insert}

Inserts operator into collection.

```csharp
public override void Insert(int index, Operator op)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Index where new operator must be added |
| op | Operator | Operator which will be insterted |

## Examples {#examples}

Example demonstrates how to insert operator to the page contents.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### See Also {#see-also}

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Insert operators at the the given position.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| at | Int32 | Index from which operators are being started to insert. |
| ops | Operator[] | Array of operators to be inserted. Each operator can have any index (by default -1) because their indices adjusted automatically starting from *at*. |

## Examples {#examples-1}

Example demonstrates how to insert operator to the page contents.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### See Also {#see-also-1}

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList<Operator>) {#insert_2}

Insert operators at the the given position.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| at | Int32 | Index from which operators are being started to insert. |
| ops | IList`1 | Array of operators to be inserted. |

## Examples {#examples-2}

Example demonstrates how to insert operators to page contents.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### See Also {#see-also-2}

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
