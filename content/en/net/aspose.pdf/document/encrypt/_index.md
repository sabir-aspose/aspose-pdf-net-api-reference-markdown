---
title: "Document.Encrypt"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Encrypts the document"
type: docs
url: "/net/aspose.pdf/document/encrypt/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/document/encrypt/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:54:11+00:00"
---
## Encrypt(Permissions, CryptoAlgorithm, IList<X509Certificate2>) {#encrypt}

Encrypts the document.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| Parameter | Type | Description |
| --- | --- | --- |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |
| publicCertificates | IList`1 | The public certificates used for encryption — one per recipient. |

## Remarks {#remarks}

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

### See Also {#see-also}

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

Encrypts the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privileges | DocumentPrivilege | Document permissions, see [`Permissions`](../permissions/) for details. |
| customHandler | ICustomSecurityHandler | The custom security handler. |

## Remarks {#remarks-1}

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

### See Also {#see-also-1}

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

Encrypts the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| customHandler | ICustomSecurityHandler | The custom security handler. |

## Remarks {#remarks-2}

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

### See Also {#see-also-2}

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

Encrypts the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privileges | DocumentPrivilege | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |
| usePdf20 | Boolean | Support for revision 6 (Extension 8). |

## Remarks {#remarks-3}

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

### See Also {#see-also-3}

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

Encrypts the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |

## Remarks {#remarks-4}

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

### See Also {#see-also-4}

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

Encrypts the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |
| usePdf20 | Boolean | Support for revision 6 (Extension 8). |

## Remarks {#remarks-5}

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

### See Also {#see-also-5}

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
