---
title: "Enum KeySize"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.KeySize enum. Defines different key sizes which can be used to encrypt pdf documents"
type: docs
url: "/net/aspose.pdf.facades/keysize/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/keysize/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:14:21+00:00"
---
## KeySize enumeration {#keysize-enumeration}

Defines different key sizes which can be used to encrypt pdf documents.

```csharp
public enum KeySize
```

### Values {#values}

| Name | Value | Description |
| --- | --- | --- |
| x40 | `0` | 40 bit key. Such key size is used with RC4 algorithm and provides low level of security. Nevertheless old versions of pdf documents can be encrypted only with such keys (v. 1.3 and lower); |
| x128 | `1` | 128 bit key. Both RC4 and AES algorithms can use such key size. |
| x256 | `2` | 256 bit key. Such key size can be used only with AES and is recognized with the last Adobe Reader versions (starting from v.9). |

### See Also {#see-also}

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)
