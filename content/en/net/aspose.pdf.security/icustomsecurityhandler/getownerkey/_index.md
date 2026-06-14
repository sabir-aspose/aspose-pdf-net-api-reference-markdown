---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in CalculateEncryptionKey to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified"
type: docs
url: "/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:26+00:00"
---
## ICustomSecurityHandler.GetOwnerKey method {#icustomsecurityhandlergetownerkey-method}

Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in [`CalculateEncryptionKey`](../calculateencryptionkey/) to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | The user password. |
| ownerPassword | String | The owner password. |

### Return Value {#return-value}

The array of owner key.

### See Also {#see-also}

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)
