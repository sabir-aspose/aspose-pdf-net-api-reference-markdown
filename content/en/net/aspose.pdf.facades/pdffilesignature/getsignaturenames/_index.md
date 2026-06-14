---
title: "PdfFileSignature.GetSignatureNames"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSignature method. Gets the names of all not empty signatures"
type: docs
url: "/net/aspose.pdf.facades/pdffilesignature/getsignaturenames/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesignature/getsignaturenames/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:42+00:00"
---
## PdfFileSignature.GetSignatureNames method {#pdffilesignaturegetsignaturenames-method}

Gets the names of all not empty signatures.

```csharp
public IList<SignatureName> GetSignatureNames(bool onlyActive = true)
```

| Parameter | Type | Description |
| --- | --- | --- |
| onlyActive | Boolean | if true, return only active signatures; otherwise, return all signatures. |

### Return Value {#return-value}

Return an IList<SignatureName>.

## Examples {#examples}

```csharp
[C#]
string inFile=TestPath + "example1.pdf";
PdfFileSignature pdfSign=new PdfFileSignature();
pdfSign.BindPdf(inFile); 
var names=pdfSign.GetSignatureNames();
or(int i=0;i<names.Count;i++)

 Console.WriteLine("signature name:" + names[i]);
 Console.WriteLine("coverswholedocument:" + pdfSign.CoversWholeDocument(names[i]));
 Console.WriteLine("revision:" + pdfSign.GetRevision(names[i]));	
 Console.WriteLine("verifysigned:" + pdfSign.VerifySignature(names[i]));
 Console.WriteLine("reason:" + pdfSign.GetReason(names[i]));
 Console.WriteLine("location:" + pdfSign.GetLocation(names[i]));
 Console.WriteLine("datatime:" + pdfSign.GetDateTime(names[i]));		
}
Console.WriteLine("totalvision:" + pdfSign.GetTotalRevision());
[Visual Basic]
Dim pdfSign as PdfFileSignature =new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names=pdfSign.GetSignNames()
For i=0 To names.Count

	Console.WriteLine("signature name:" + (SignatureName)names[i])
	Console.WriteLine("coverswholedocument:" + pdfSign.IsCoversWholeDocument((string)names[i]))
	Console.WriteLine("revision:" + pdfSign.GetRevision((SignatureName)names[i]))	
	Console.WriteLine("verifysigned:" + pdfSign.VerifySignature((SignatureName)names[i]))
	Console.WriteLine("reason:" + pdfSign.GetReason((SignatureName)names[i]))
	Console.WriteLine("location:" + pdfSign.GetLocation((SignatureName)names[i]))
	Console.WriteLine("datatime:" + pdfSign.GetDateTime((SignatureName)names[i]))	
Next i
Console.WriteLine("totalvision:" + pdfSign.GetTotalRevision())
```

### See Also {#see-also}

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
