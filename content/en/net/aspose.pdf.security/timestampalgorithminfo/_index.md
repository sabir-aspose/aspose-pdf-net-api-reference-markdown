---
title: "Class TimestampAlgorithmInfo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Security.TimestampAlgorithmInfo class. Represents a class for the information about the timestamp signature algorithm"
type: docs
url: "/net/aspose.pdf.security/timestampalgorithminfo/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/timestampalgorithminfo/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:39+00:00"
---
## TimestampAlgorithmInfo class {#timestampalgorithminfo-class}

Represents a class for the information about the timestamp signature algorithm.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Gets the hash algorithm that hashed the content of the document and then signed it using [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. For a timestamp, this is the digest hash algorithm with which the hash of the document content is signed. |

### See Also {#see-also}

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)
