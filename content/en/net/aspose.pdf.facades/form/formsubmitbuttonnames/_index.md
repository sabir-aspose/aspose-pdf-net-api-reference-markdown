---
title: "Form.FormSubmitButtonNames"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form property. Gets all form submit button names"
type: docs
url: "/net/aspose.pdf.facades/form/formsubmitbuttonnames/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/formsubmitbuttonnames/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:45+00:00"
---
## Form.FormSubmitButtonNames property {#formformsubmitbuttonnames-property}

Gets all form submit button names.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Examples {#examples}

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
