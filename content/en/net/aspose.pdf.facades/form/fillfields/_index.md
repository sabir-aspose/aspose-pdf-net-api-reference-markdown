---
title: "Form.FillFields"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice Only be applied to Text Box. Both the fields name and values are case sensitive"
type: docs
url: "/net/aspose.pdf.facades/form/fillfields/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/form/fillfields/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:12:42+00:00"
---
## Form.FillFields method {#formfillfields-method}

Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to Text Box. Both the fields’ name and values are case sensitive.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldNames | String[] | Names of fields. |
| fieldValues | String[] | New values of the fields. |
| output | Stream& | Stream where document will be saved. |

### Return Value {#return-value}

true if fields was found and successfully filled.

## Examples {#examples}

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### See Also {#see-also}

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
