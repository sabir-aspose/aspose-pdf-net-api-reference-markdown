---
title: "PdfFileSecurity.TryDecryptFile"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSecurity method. Decrypts an encrypted Pdf document by owner password. If the document hasnt owner password it is allow to use user password. Does not throw an exception if process failed"
type: docs
url: "/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:29+00:00"
---
## PdfFileSecurity.TryDecryptFile method {#pdffilesecuritytrydecryptfile-method}

Decrypts an encrypted Pdf document by owner password. If the document hasn’t owner password, it is allow to use user password. Does not throw an exception if process failed.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Owner password. |

### Return Value {#return-value}

True for success,or false.

## Examples {#examples}

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### See Also {#see-also}

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
