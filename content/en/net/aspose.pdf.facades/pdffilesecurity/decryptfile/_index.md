---
title: "PdfFileSecurity.DecryptFile"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSecurity method. Decrypts an encrypted Pdf document by owner password. If the document hasnt owner password it is allow to use user password. Throws an exception if process failed"
type: docs
url: "/net/aspose.pdf.facades/pdffilesecurity/decryptfile/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesecurity/decryptfile/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:24+00:00"
---
## PdfFileSecurity.DecryptFile method {#pdffilesecuritydecryptfile-method}

Decrypts an encrypted Pdf document by owner password. If the document hasn’t owner password, it is allow to use user password. Throws an exception if process failed.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Owner password. |

### Return Value {#return-value}

True for success.

## Examples {#examples}

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### See Also {#see-also}

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
