---
title: "Document.SaveAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Saves the document with a new name setting its save options"
type: docs
url: "/net/aspose.pdf/document/saveasync/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/document/saveasync/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:54:46+00:00"
---
## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Saves the document with a new name setting its save options.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |
| options | SaveOptions | Save options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value {#return-value}

Asynchronous task.

### See Also {#see-also}

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Saves the document to a stream with a save options.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| options | SaveOptions | Save options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value {#return-value-1}

Asynchronous task.

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

## SaveAsync(CancellationToken) {#saveasync_7}

Save document incrementally (i.e. using incremental update technique).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value {#return-value-2}

Asynchronous task.

## Remarks {#remarks}

In order to save document incrementally we should open the document file for writing. Therefore Document must be initialized with writable stream like in the next code snippet: Document doc = new Document(new FileStream(“document.pdf”, FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save();

### See Also {#see-also-2}

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Saves the document with save options.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Save options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value {#return-value-3}

Asynchronous task.

### See Also {#see-also-3}

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Saves the document with a new name along with a file format.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |
| format | SaveFormat | Format options. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value {#return-value-4}

Asynchronous task.

### See Also {#see-also-4}

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Saves the document with a new name along with a file format.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where the document will be stored. |
| format | SaveFormat | Format options. |
| cancellationToken | CancellationToken | Cancellation token |

### Return Value {#return-value-5}

Asynchronous task.

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

## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Stores document into stream.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| output | Stream | Stream where document shell be stored. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value {#return-value-6}

Asynchronous task.

### See Also {#see-also-6}

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Saves document into the specified file.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | Path to file where the document will be stored. |
| cancellationToken | CancellationToken | Caclellation token. |

### Return Value {#return-value-7}

Asynchronous task.

### See Also {#see-also-7}

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
