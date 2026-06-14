---
title: "Class RsaAlgorithmInfo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Security.RsaAlgorithmInfo class. Represents a class for the information about the RSA signature algorithm"
type: docs
url: "/net/aspose.pdf.security/rsaalgorithminfo/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/rsaalgorithminfo/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:34+00:00"
---
## RsaAlgorithmInfo class {#rsaalgorithminfo-class}

Represents a class for the information about the RSA signature algorithm.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Gets the name of the signature field. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Converts the current information object to its string representation. |

## Fields {#fields}

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Gets the type of the signature algorithm used for signing the PDF document. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. For a timestamp, this is the digest hash algorithm with which the hash of the document content is signed. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Gets the size of the cryptographic key used by the signature algorithm. |

### See Also {#see-also}

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)
