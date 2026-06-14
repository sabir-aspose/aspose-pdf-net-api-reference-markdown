---
title: "Document.Convert"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Convert document and save errors into the specified file"
type: docs
url: "/net/aspose.pdf/document/convert/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/document/convert/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:54:01+00:00"
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Convert document and save errors into the specified file.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | Path to file where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### Return Value {#return-value}

The operation result

### See Also {#see-also}

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Convert document and save errors into the specified file.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | Stream where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### Return Value {#return-value-1}

The operation result

### See Also {#see-also-1}

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Convert document and save errors into the specified file.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | Path to file where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |

### Return Value {#return-value-2}

The operation result

### See Also {#see-also-2}

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Convert document using specified conversion options

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | PdfFormatConversionOptions | set of options for convert PDF document |

### Return Value {#return-value-3}

The operation result

### See Also {#see-also-3}

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Recognize images inside the document and add hocr strings over it.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Action for images that will be processed by hocr recognize. |
| flattenImages | Boolean | Text in pdf images can be painted using the mechanics of masks, in which case the images must be flattened. |

### Return Value {#return-value-4}

The operation result. If there are no images in the document returns !:false.

### See Also {#see-also-4}

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Recognize images inside the document and add hocr strings over it.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocr | Action for images that will be processed by hocr recognize. |
| flattenImages | Boolean | Text in pdf images can be painted using the mechanics of masks, in which case the images must be flattened. |

### Return Value {#return-value-5}

The operation result. If there are no images in the document returns !:false.

### See Also {#see-also-5}

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Convert document and save errors into the specified stream.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | Stream where the comments will be stored. |
| format | PdfFormat | Pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |

### Return Value {#return-value-6}

The operation result

### See Also {#see-also-6}

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Convert document by applying the Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | Stream | The log of process. |
| onlyValidation | Boolean | Only document validation. |
| parameters | Object[] | Properties for Fixup that can not be set. |

### Return Value {#return-value-7}

The operation result.

### See Also {#see-also-7}

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Convert document by applying the Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | String | The log of process. |
| onlyValidation | Boolean | Only document validation. |
| parameters | Object[] | Properties for Fixup that can not be set. |

### Return Value {#return-value-8}

The operation result.

### See Also {#see-also-8}

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Converts source file in source format into destination file in destination format.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The source file name. |
| loadOptions | LoadOptions | The source file format. |
| dstFileName | String | The destination file name. |
| saveOptions | SaveOptions | The destination file format. |

### See Also {#see-also-9}

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Converts stream in source format into destination file in destination format.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | The source stream. |
| loadOptions | LoadOptions | The source stream format. |
| dstFileName | String | The destination file name. |
| saveOptions | SaveOptions | The destination file format. |

### See Also {#see-also-10}

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Converts source file in source format into stream in destination format.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The source file name. |
| loadOptions | LoadOptions | The source file format. |
| dstStream | Stream | The destination stream. |
| saveOptions | SaveOptions | The destination stream format. |

### See Also {#see-also-11}

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Converts stream in source format into stream in destination format.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | The source stream. |
| loadOptions | LoadOptions | The source stream format. |
| dstStream | Stream | The destination stream. |
| saveOptions | SaveOptions | The destination file format. |

### See Also {#see-also-12}

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
