---
title: "Class FdfReader"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.FdfReader class. Class which performes reading of FDF format"
type: docs
url: "/net/aspose.pdf.annotations/fdfreader/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.annotations/fdfreader/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:01:14+00:00"
---
## FdfReader class {#fdfreader-class}

Class which performes reading of FDF format.

```csharp
public sealed class FdfReader
```

## Methods {#methods}

| Name | Description |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Import annotations from FDF file and put them into document. |

## Examples {#examples}

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### See Also {#see-also}

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)
