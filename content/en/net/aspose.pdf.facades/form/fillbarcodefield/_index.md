---
title: "Form.FillBarcodeField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Fill a barcode field according to its fully qualified field name"
type: docs
url: "/net/aspose.pdf.facades/form/fillbarcodefield/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/fillbarcodefield/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:40+00:00"
---
## Form.FillBarcodeField method {#formfillbarcodefield-method}

Fill a barcode field according to its fully qualified field name.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |
| data | String | The new barcode value. |

### Return Value {#return-value}

If filling succeed, return true; otherwise, false.

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
