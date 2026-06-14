---
title: "ICustomSecurityHandler.Encrypt"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Encrypt the data array"
type: docs
url: "/net/aspose.pdf.security/icustomsecurityhandler/encrypt/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/icustomsecurityhandler/encrypt/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:24+00:00"
---
## ICustomSecurityHandler.Encrypt method {#icustomsecurityhandlerencrypt-method}

Encrypt the data array.

```csharp
public byte[] Encrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | Byte[] | Data to encrypt. |
| objectNumber | Int32 | Number of the object containing the encrypted data. |
| generation | Int32 | Generation of the object. |
| key | Byte[] | Key obtained by the CalculateEncryptionKey method |

### Return Value {#return-value}

The encrypted data.

### See Also {#see-also}

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)
