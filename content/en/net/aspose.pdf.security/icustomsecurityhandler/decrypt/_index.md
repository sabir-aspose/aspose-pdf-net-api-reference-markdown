---
title: "ICustomSecurityHandler.Decrypt"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Decrypt the data array"
type: docs
url: "/net/aspose.pdf.security/icustomsecurityhandler/decrypt/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/icustomsecurityhandler/decrypt/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:23+00:00"
---
## ICustomSecurityHandler.Decrypt method {#icustomsecurityhandlerdecrypt-method}

Decrypt the data array.

```csharp
public byte[] Decrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | Byte[] | Data to decrypt. |
| objectNumber | Int32 | Number of the object containing the encrypted data. |
| generation | Int32 | Generation of the object. |
| key | Byte[] | Key obtained by the CalculateEncryptionKey method |

### Return Value {#return-value}

The decrypted data.

### See Also {#see-also}

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)
