---
title: "Form.Form"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form constructor. Construtcor of Form without parameters"
type: docs
url: "/net/aspose.pdf.facades/form/form/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/form/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:44+00:00"
---
## Form() {#constructor}

Construtcor of Form without parameters.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Constructor of Form.

```csharp
public Form(string srcFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | Source file path. |

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
```

### See Also {#see-also-1}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Constructor for form.

```csharp
public Form(Stream srcStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | source stream. |

## Examples {#examples-1}

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### See Also {#see-also-2}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Initializes new [`Form`](../) object on base of the *document*.

```csharp
public Form(Document document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Pdf document. |

### See Also {#see-also-3}

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
