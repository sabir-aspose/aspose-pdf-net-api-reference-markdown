---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Aspose.PDF for .NET API Reference"
description: "HtmlSaveOptions field. This field can contain custom method that returns URL Or URL template if multipage generation is on see details below of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS then You should just create and put into this property method that generates desirable URL. If flag SplitCssIntoPages set then this custom strategy if any must return not exact URL of CSS but rather template string that after substitution of placeholder with page number with string.Format function inside converter can be resolved into URL for this or that pages CSS URL. Examples of expected return string in such case are SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
url: "/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:57:52+00:00"
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field {#htmlsaveoptionscustomstrategyofcssurlcreation-field}

This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag ‘SplitCssIntoPages’ set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with string.Format() function inside converter) can be resolved into URL for this or that page’s CSS’ URL. Examples of expected return string in such case are: ‘SomeTargetLocation-page_{0}.css’,’../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0}’)

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### See Also {#see-also}

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
