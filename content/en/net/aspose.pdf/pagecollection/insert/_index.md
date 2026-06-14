---
title: "PageCollection.Insert"
second_title: "Aspose.PDF for .NET API Reference"
description: "PageCollection method. Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes the size of the most frequently occurring page will be selected. In the case there are only two different pages the size of the first page will be used"
type: docs
url: "/net/aspose.pdf/pagecollection/insert/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/pagecollection/insert/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:04:37+00:00"
---
## Insert(int) {#insert}

Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Position of the new page. |

### Return Value {#return-value}

Inserted page.

### See Also {#see-also}

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Inserts page into page collection at specified place.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Required page index in collection. |
| entity | Page | Page to be inserted. |

### Return Value {#return-value-1}

Inserted page.

### See Also {#see-also-1}

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection<Page>) {#insert_3}

Inserts pages from the collection into document.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Starting position of the new pages. |
| pages | ICollection`1 | Pages collection. |

### See Also {#see-also-2}

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Inserts pages of the array into document.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Starting number of the new pages. |
| pages | Page[] | Array of pages which will be inserted. |

### See Also {#see-also-3}

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
