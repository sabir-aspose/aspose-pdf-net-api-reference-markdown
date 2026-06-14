---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSecurity method. Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed"
type: docs
url: "/net/aspose.pdf.facades/pdffilesecurity/setprivilege/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesecurity/setprivilege/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:27+00:00"
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value {#return-value}

True for success.

## Examples {#examples}

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### See Also {#see-also}

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Sets Pdf file security with original password. Throws an exception if process failed.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | Original user password. |
| ownerPassword | String | Original owner password. |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value {#return-value-1}

True for success.

## Examples {#examples-1}

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### See Also {#see-also-1}

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
