---
title: "Class Id"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Id class. Represents file identifier structure"
type: docs
url: "/net/aspose.pdf/id/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/id/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:58:24+00:00"
---
## Id class {#id-class}

Represents file identifier structure.

```csharp
public class Id
```

## Properties {#properties}

| Name | Description |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Changing identifier based on the document’s contents at the time it was last updated. |
| [Original](../../aspose.pdf/id/original/) { get; } | Permanent identifier based on the contents of the document at the time it was originally created. |

## Examples {#examples}

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### See Also {#see-also}

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
