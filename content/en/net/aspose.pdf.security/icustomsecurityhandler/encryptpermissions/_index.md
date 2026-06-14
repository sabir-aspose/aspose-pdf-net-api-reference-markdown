---
title: "ICustomSecurityHandler.EncryptPermissions"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Encrypt the documents permissions field. The result will be written to the Perms encryption dictionary field. When opening a document the value can be obtained in EncryptionParameters via the Perms field. Allows you to check if the document permissions have changed"
type: docs
url: "/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:25+00:00"
---
## ICustomSecurityHandler.EncryptPermissions method {#icustomsecurityhandlerencryptpermissions-method}

Encrypt the document’s permissions field. The result will be written to the Perms encryption dictionary field. When opening a document, the value can be obtained in [`EncryptionParameters`](../../encryptionparameters/) via the Perms field. Allows you to check if the document permissions have changed.

```csharp
public byte[] EncryptPermissions(int permissions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| permissions | Int32 | The document permissions in integer representation. |

### Return Value {#return-value}

The encrypted array.

### See Also {#see-also}

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)
