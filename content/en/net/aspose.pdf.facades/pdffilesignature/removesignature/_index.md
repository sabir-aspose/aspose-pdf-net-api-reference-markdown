---
title: "PdfFileSignature.RemoveSignature"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSignature method. Remove the signature according to the name of the signature"
type: docs
url: "/net/aspose.pdf.facades/pdffilesignature/removesignature/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesignature/removesignature/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:47+00:00"
---
## RemoveSignature(SignatureName) {#removesignature}

Remove the signature according to the name of the signature.

```csharp
public void RemoveSignature(SignatureName signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |

## Examples {#examples}

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
IList<SignatureName> names = pdfSign.GetSignatureNames();
for(int i = 0; i < names.Count; i++)
{
   pdfSign.RemoveSignature(names[i]);
}
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names = pdfSign.GetSignatureNames()
For i = 0 To names.Count
 pdfSign.RemoveSignature((SignatureName)names[i])
Next i
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### See Also {#see-also}

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

Removes the signature according to the name of the signature.

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| removeField | Boolean | If set to true, than removes both of signature and field from document; otherwise, signature only. |

## Examples {#examples-1}

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
IList<SignatureName> names = pdfSign.GetSignatureNames();
for(int i = 0; i < names.Count; i++)
{
   pdfSign.RemoveSignature(names[i], false);
}
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names = pdfSign.GetSignNames()
For i = 0 To names.Count
 pdfSign.RemoveSignature((SignatureName)names[i], false)
Next i
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### See Also {#see-also-1}

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
