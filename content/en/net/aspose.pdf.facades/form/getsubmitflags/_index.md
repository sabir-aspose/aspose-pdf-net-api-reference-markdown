---
title: "Form.GetSubmitFlags"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns the submit buttons submission flags"
type: docs
url: "/net/aspose.pdf.facades/form/getsubmitflags/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/getsubmitflags/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:53+00:00"
---
## Form.GetSubmitFlags method {#formgetsubmitflags-method}

Returns the submit button’s submission flags

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |

### Return Value {#return-value}

Submission flags of the button.

## Examples {#examples}

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### See Also {#see-also}

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
