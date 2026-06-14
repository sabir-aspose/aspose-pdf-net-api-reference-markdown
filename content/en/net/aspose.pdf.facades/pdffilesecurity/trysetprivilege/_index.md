---
title: "PdfFileSecurity.TrySetPrivilege"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSecurity method. Sets Pdf file security with original password. Does not throw an exception if process failed"
type: docs
url: "/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:30+00:00"
---
## PdfFileSecurity.TrySetPrivilege method {#pdffilesecuritytrysetprivilege-method}

Sets Pdf file security with original password. Does not throw an exception if process failed.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | Original user password. |
| ownerPassword | String | Original owner password. |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value {#return-value}

True for success, or false.

## Examples {#examples}

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### See Also {#see-also}

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
