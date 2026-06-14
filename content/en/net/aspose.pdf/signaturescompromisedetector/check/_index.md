---
title: "SignaturesCompromiseDetector.Check"
second_title: "Aspose.PDF for .NET API Reference"
description: "SignaturesCompromiseDetector method. Check the digital signatures of the document for compromise"
type: docs
url: "/net/aspose.pdf/signaturescompromisedetector/check/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/signaturescompromisedetector/check/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:08:35+00:00"
---
## SignaturesCompromiseDetector.Check method {#signaturescompromisedetectorcheck-method}

Check the digital signatures of the document for compromise.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | The result of verification of the document. |

### Return Value {#return-value}

True, if the compromise of the signatures is not detected.

## Remarks {#remarks}

The using of this method for a document in which there are no digital signatures will return `True`.

### See Also {#see-also}

* class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* class [SignaturesCompromiseDetector](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
