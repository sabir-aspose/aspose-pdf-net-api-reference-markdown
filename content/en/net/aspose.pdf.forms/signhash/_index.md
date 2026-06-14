---
title: "Delegate SignHash"
second_title: "Aspose.PDF for .NET API Reference"
description: "Delegate for custom sign the document hash"
type: docs
url: "/net/aspose.pdf.forms/signhash/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.forms/signhash/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:23:19+00:00"
---
## SignHash delegate {#signhash-delegate}

Delegate for custom sign the document hash.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Type | Description |
| --- | --- | --- |
| hash | Byte[] | Input hash of the document. |
| digestHashAlgorithm | DigestHashAlgorithm | The digest algorithm used to create the hash. The value will never be equal to Auto. |

### Return Value {#return-value}

Output signature.

## Remarks {#remarks}

Note that whether the digital signature is detached or not, the hash argument will always be the final hash to be signed.

### See Also {#see-also}

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)
