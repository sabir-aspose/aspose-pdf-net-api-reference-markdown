---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Resizes page contents and add specified margins. Margins are specified in percents of intitial page size"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/addmarginspct/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/addmarginspct/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:04+00:00"
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream which contains source document. |
| destination | Stream | Stream where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | Double | Left margin in percents of initial page size. |
| rightMargin | Double | Right margin in percents of initial page size. |
| topMargin | Double | Top margin in percents of initial page size. |
| bottomMargin | Double | Bottom margin in percents of initial page size. |

### Return Value {#return-value}

true if action was performed successfully.

## Examples {#examples}

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Path to source document. |
| destination | String | Path where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | Double | Left margin in percents of initial page size. |
| rightMargin | Double | Right margin in percents of initial page size. |
| topMargin | Double | Top margin in percents of initial page size. |
| bottomMargin | Double | Bottom margin in percents of initial page size. |

### Return Value {#return-value-1}

true if resize was successful

## Examples {#examples-1}

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### See Also {#see-also-1}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
