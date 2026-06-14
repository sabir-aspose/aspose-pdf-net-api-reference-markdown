---
title: "Stamp.BindImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "Stamp method. Sets image as a stamp"
type: docs
url: "/net/aspose.pdf.facades/stamp/bindimage/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/stamp/bindimage/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:19:39+00:00"
---
## BindImage(string) {#bindimage_1}

Sets image as a stamp.

```csharp
public void BindImage(string imageFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Image file name and path. |

## Examples {#examples}

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also {#see-also}

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Sets image which will be used as stamp.

```csharp
public void BindImage(Stream image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Stream | Stream which contains image data. |

### See Also {#see-also-1}

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
