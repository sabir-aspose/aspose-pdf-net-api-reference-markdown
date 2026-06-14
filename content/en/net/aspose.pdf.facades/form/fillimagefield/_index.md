---
title: "Form.FillImageField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Pastes an image onto the existing button field as its appearance according to its fully qualified field name"
type: docs
url: "/net/aspose.pdf.facades/form/fillimagefield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/fillimagefield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:42+00:00"
---
## FillImageField(string, string) {#fillimagefield_1}

Pastes an image onto the existing button field as its appearance according to its fully qualified field name.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name of the image button field. |
| imageFileName | String | The path of the image file, relative and absolute are both ok. |

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Overloads function of FillImageField. The input is a image stream.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |
| imageStream | Stream | The image’s stream. |

## Examples {#examples-1}

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### See Also {#see-also-1}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
