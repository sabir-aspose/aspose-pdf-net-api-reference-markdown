---
title: "Signature.Verify"
second_title: "Aspose.PDF for .NET API Reference"
description: "Signature method. Verify the document regarding this signature and return true if document is valid or otherwise false"
type: docs
url: "/net/aspose.pdf.forms/signature/verify/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.forms/signature/verify/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:22:59+00:00"
---
## Verify() {#verify}

Verify the document regarding this signature and return true if document is valid or otherwise false.

```csharp
public bool Verify()
```

### Return Value {#return-value}

true if document is valid.

### See Also {#see-also}

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Verify the document regarding this signature and return true if document is valid or otherwise false.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |

### Return Value {#return-value-1}

true if document is valid.

### See Also {#see-also-1}

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

Verify the document regarding this signature and return true if document is valid or otherwise false. Verification is performed using the external public key certificate.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |

### Return Value {#return-value-2}

true if document is valid.

### See Also {#see-also-2}

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)
