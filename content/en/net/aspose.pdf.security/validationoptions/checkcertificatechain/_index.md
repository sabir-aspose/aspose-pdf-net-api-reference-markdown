---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Aspose.PDF for .NET API Reference"
description: "ValidationOptions property. Gets or sets a value indicating whether the certificate chain should be checked during the validation process"
type: docs
url: "/net/aspose.pdf.security/validationoptions/checkcertificatechain/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security/validationoptions/checkcertificatechain/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:44+00:00"
---
## ValidationOptions.CheckCertificateChain property {#validationoptionscheckcertificatechain-property}

Gets or sets a value indicating whether the certificate chain should be checked during the validation process.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Remarks {#remarks}

When the property is set, the existence of a chain of certificates will be checked, if it is absent, then the result of the verification will be Undefined, which corresponds to the behavior of Adobe Acrobat. If you just want to check the status of revocation online, then set the field in `false`. The default value is `false`.

### See Also {#see-also}

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)
