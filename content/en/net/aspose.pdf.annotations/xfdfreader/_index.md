---
title: "Class XfdfReader"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.XfdfReader class. Class which peroformes reading of XFDF format"
type: docs
url: "/net/aspose.pdf.annotations/xfdfreader/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.annotations/xfdfreader/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:07:44+00:00"
---
## XfdfReader class {#xfdfreader-class}

Class which peroformes reading of XFDF format.

```csharp
public sealed class XfdfReader
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [XfdfReader](xfdfreader/)() | The default constructor. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Parses XFDF file and returns information as hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Import annotations from XFDF file and put them into document. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Import field values from XFDF file. |

## Examples {#examples}

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### See Also {#see-also}

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)
