---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF for .NET API Reference"
description: "ICustomSecurityHandler method. Creates an encoded array based on the users password. This value is typically used to check if the password belongs to the user or owner and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The userspecified password is passed as an argument when calling document encryption"
type: docs
url: "/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:27+00:00"
---
## ICustomSecurityHandler.GetUserKey method {#icustomsecurityhandlergetuserkey-method}

Creates an encoded array based on the user’s password. This value is typically used to check if the password belongs to the user or owner, and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The user-specified password is passed as an argument when calling document encryption.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | The user password. |

### Return Value {#return-value}

The array of user key.

### See Also {#see-also}

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)
