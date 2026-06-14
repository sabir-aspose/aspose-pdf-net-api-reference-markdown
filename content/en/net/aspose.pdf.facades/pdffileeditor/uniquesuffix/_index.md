---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor property. Format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain NUM substring which will be replaced with numbers. For example if UniqueSuffix ABCNUM then for field fieldName names will be fieldNameABC1 fieldNameABC2 fieldNameABC3 etc"
type: docs
url: "/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:16:39+00:00"
---
## PdfFileEditor.UniqueSuffix property {#pdffileeditoruniquesuffix-property}

Format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = “ABC%NUM%” then for field “fieldName” names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

```csharp
public string UniqueSuffix { get; set; }
```

## Examples {#examples}

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### See Also {#see-also}

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
