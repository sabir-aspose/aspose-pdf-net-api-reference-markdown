---
title: "Document.Save"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Saves the document with a new name setting its save options"
type: docs
url: "/net/aspose.pdf/document/save/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/document/save/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:54:46+00:00"
---
## Save(string, SaveOptions) {#save_7}

Saves the document with a new name setting its save options.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |
| options | SaveOptions | Save options. |

### See Also {#see-also}

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Saves the document to a stream with a save options.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| options | SaveOptions | Save options. |

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException when [`HtmlSaveOptions`](../../htmlsaveoptions/) is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also {#see-also-1}

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Save document incrementally (i.e. using incremental update technique).

```csharp
public void Save()
```

## Remarks {#remarks}

In order to save document incrementally we should open the document file for writing. Therefore Document must be initialized with writable stream like in the next code snippet: Document doc = new Document(new FileStream(“document.pdf”, FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save();

### See Also {#see-also-2}

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Saves the document with save options.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Save options. |

### See Also {#see-also-3}

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Saves the document with a new name along with a file format.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |
| format | SaveFormat | Format options. |

### See Also {#see-also-4}

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Saves the document with a new name along with a file format.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| format | SaveFormat | Format options. |

### Exceptions {#exceptions-1}

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException when [`HtmlSaveOptions`](../../htmlsaveoptions/) is passed to a method. Save a document to the html stream is not supported. Please use method save to the file. |

### See Also {#see-also-5}

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Stores document into stream.

```csharp
public void Save(Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| output | Stream | Stream where document shell be stored. |

### See Also {#see-also-6}

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Saves document into the specified file.

```csharp
public void Save(string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |

### See Also {#see-also-7}

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
