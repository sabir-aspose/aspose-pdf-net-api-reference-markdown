---
title: "ComHelper.OpenFile"
second_title: "Aspose.PDF for .NET API Reference"
description: "ComHelper method. Just create and return Document using filename. The same as Document"
type: docs
url: "/net/aspose.pdf/comhelper/openfile/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/comhelper/openfile/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:53:07+00:00"
---
## OpenFile(string) {#openfile}

Just create and return Document using *filename*. The same as [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The name of the pdf document file. |

### Return Value {#return-value}

Document object

### See Also {#see-also}

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Initialize and return new instance of the [`Document`](../../document/) class for working with encrypted document.

```csharp
public Document OpenFile(string filename, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | Document file name. |
| password | String | User or owner password. |

### Return Value {#return-value-1}

Document object

### See Also {#see-also-1}

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Initialize new instance of the [`Document`](../../document/) class for working with encrypted document.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | Document file name. |
| password | String | User or owner password. |
| isManagedStream | Boolean | if set to `true` inner stream is closed before exit; otherwise, is not. |

### Return Value {#return-value-2}

Document object

### See Also {#see-also-2}

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Open an existing document from a file providing necessary converting oprions to get pdf document.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | Input file to convert into pdf document. |
| options | LoadOptions | Represents properties for converting *filename* into pdf document. |

### Return Value {#return-value-3}

Document object

### See Also {#see-also-3}

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
