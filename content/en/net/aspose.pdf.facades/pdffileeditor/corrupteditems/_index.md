---
title: "PdfFileEditor.CorruptedItems"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor property. Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate function new CorruptedItem entry is created. This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/corrupteditems/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/corrupteditems/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:12+00:00"
---
## PdfFileEditor.CorruptedItems property {#pdffileeditorcorrupteditems-property}

Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate() function new CorruptedItem entry is created. This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted.

```csharp
//concatenate documents and show information about corrupted documents
PdfFileEditor pfe = new PdfFileEditor();
pfe.CorruptedFileAction = PdfFileEditor.ConcatenateCorruptedFileActions.ConcatenateIgnoringCorrupted;
if (pfe.CorruptedItems.Length >0)
{
  foreach(PdfFileEditor.CorruptedItem item in pfe.CorruptedItems)
  {
     Console.WriteLine(item.Index + " reason: " + item.Exception);
  }
}
```

```csharp
public CorruptedItem[] CorruptedItems { get; }
```

### See Also {#see-also}

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
