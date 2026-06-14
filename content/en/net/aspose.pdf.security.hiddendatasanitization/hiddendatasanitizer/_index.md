---
title: "Class HiddenDataSanitizer"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Security.HiddenDataSanitization.HiddenDataSanitizer class. Represents a class for sanitizing hidden data"
type: docs
url: "/net/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:41:07+00:00"
---
## HiddenDataSanitizer class {#hiddendatasanitizer-class}

Represents a class for sanitizing hidden data.

```csharp
public sealed class HiddenDataSanitizer
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [HiddenDataSanitizer](hiddendatasanitizer/)(HiddenDataSanitizationOptions) | Provides functionality to sanitize hidden data from a PDF document, ensuring that sensitive or unnecessary information such as metadata, annotations, JavaScripts, or private content is removed or transformed. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [Sanitize](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/sanitize/)(Document) | Sanitizes a given PDF document by removing or transforming hidden data. |
| static [SanitizeAllToImages](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/sanitizealltoimages/)(Document, int) | Replaces page content with images and removes other hidden data. Allows you to remove hidden text with a background color, as well as text hidden under images. Also completely removes all interactive elements. The document is converted to images as is, and then cleared of any remaining hidden data. If you need to clear first and then convert, use the main class method. |

### See Also {#see-also}

* namespace [Aspose.Pdf.Security.HiddenDataSanitization](../../aspose.pdf.security.hiddendatasanitization/)
* assembly [Aspose.PDF](../../)
