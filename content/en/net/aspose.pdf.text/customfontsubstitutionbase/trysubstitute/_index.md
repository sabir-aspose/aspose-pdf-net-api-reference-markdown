---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Aspose.PDF for .NET API Reference"
description: "CustomFontSubstitutionBase method. Substitutes original font with another font"
type: docs
url: "/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:43:08+00:00"
---
## CustomFontSubstitutionBase.TrySubstitute method {#customfontsubstitutionbasetrysubstitute-method}

Substitutes original font with another font.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parameter | Type | Description |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Original font specification. |
| substitutionFont | Font& | Substitution font. |

### Return Value {#return-value}

True in case substitution was successfull.

## Remarks {#remarks}

The class CustomFontSubstitutionBase should be inherited to implement custom font substitution logic. TrySubstitute method should be overridden properly: Must return true in case substitution is required. substitutionFont must be set to valid Font object. Must return false in case no substitution is required. substitutionFont may be set to null.

### See Also {#see-also}

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)
