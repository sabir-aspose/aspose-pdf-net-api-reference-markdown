---
title: "XImageCollection.Add"
second_title: "Aspose.PDF for .NET API Reference"
description: "XImageCollection method. Adds new image to Image list. This method adds image as reference to the same PdfObject which allows to decrease file size"
type: docs
url: "/net/aspose.pdf/ximagecollection/add/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/ximagecollection/add/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:11:28+00:00"
---
## Add(XImage) {#add_2}

Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size)

```csharp
public string Add(XImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | XImage | XImage to be added. |

### Return Value {#return-value}

Name of the added image.

### See Also {#see-also}

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(Stream image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream containing image data (in JPEG format). |

### Return Value {#return-value-1}

Name of the added image.

### See Also {#see-also-1}

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Object containing array of pixels and bitmap information (Width, Height, PixelFormat). |

### Return Value {#return-value-2}

Name of the added image.

### See Also {#see-also-2}

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream containing image data. |
| filterType | ImageFilterType | The image filter type. |

### Return Value {#return-value-3}

Name of the added image.

### See Also {#see-also-3}

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Object containing array of pixels and bitmap information (Width, Height, PixelFormat). |
| filterType | ImageFilterType | The image filter type. |

### Return Value {#return-value-4}

Name of the added image.

### See Also {#see-also-4}

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Adds entity to the end of the collection, so entity can be accessed by the last index.

```csharp
public void Add(Stream image, int quality)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream containing image data (in JPEG format). |
| quality | Int32 | JPEG quality. |

### See Also {#see-also-5}

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
