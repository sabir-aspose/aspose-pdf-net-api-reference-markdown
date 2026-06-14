---
title: "PdfFileSignature.VerifySignature"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSignature method. Checks the validity of a signature"
type: docs
url: "/net/aspose.pdf.facades/pdffilesignature/verifysignature/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffilesignature/verifysignature/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:17:54+00:00"
---
## VerifySignature(SignatureName) {#verifysignature}

Checks the validity of a signature.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |

### Return Value {#return-value}

Return a result of bool type.

### See Also {#see-also}

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Checks the validity of a signature.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |

### Return Value {#return-value-1}

Return a result of bool type.

## Remarks {#remarks}

This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked.

### See Also {#see-also-1}

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

Checks the validity of a signature. Verification is performed using the external public key certificate.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |

### Return Value {#return-value-2}

Return a result of bool type.

## Remarks {#remarks-1}

This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked.

### See Also {#see-also-2}

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

Checks the validity of a signature. Verification is performed using the external public key certificate.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |

### Return Value {#return-value-3}

Return a result of bool type.

### See Also {#see-also-3}

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
