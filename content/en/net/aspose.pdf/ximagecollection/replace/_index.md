---
title: "XImageCollection.Replace"
second_title: "Aspose.PDF for .NET API Reference"
description: "XImageCollection method. Replace image in collection with another image"
type: docs
url: "/net/aspose.pdf/ximagecollection/replace/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/ximagecollection/replace/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:11:39+00:00"
---
## Replace(int, Stream) {#replace}

Replace image in collection with another image.

```csharp
public void Replace(int index, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Index of collection item which will be replaced in [1..images count] range. |
| stream | Stream | Stream containing image data (in JPEG format). |

### See Also {#see-also}

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

Replace image in collection with another image.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Index of collection item which will be replaced in [1..images count] range. |
| stream | Stream | Stream containing image data (in JPEG format). |
| quality | Int32 | Quality of JPEG compression, in percent (valid vaues are 0..100). |
| isBlackAndWhite | Boolean | If true, image is compressed with CCITT compression method which provides better compression for black nad white image. May be used only for black and white images. |

### See Also {#see-also-1}

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

Replace image in collection with another image.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Index of collection item which will be replaced in [1..images count] range. |
| stream | Stream | Stream containing image data (in JPEG format). |
| quality | Int32 | JPEG quality. |

### See Also {#see-also-2}

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
