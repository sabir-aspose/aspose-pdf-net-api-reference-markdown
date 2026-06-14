---
title: "MarkupAnnotation.SetReviewState"
second_title: "Aspose.PDF for .NET API Reference"
description: "MarkupAnnotation method. Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note the state stored in other text annotation which has state and statemodel keys"
type: docs
url: "/net/aspose.pdf.annotations/markupannotation/setreviewstate/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.annotations/markupannotation/setreviewstate/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:03:07+00:00"
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note, the state stored in other text annotation which has state and statemodel keys.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Status for assignment. |
| userName | String | The username that appears in the comments header. The name can be the same as the name in the Title of the target annotation or different if the status is set by another user. |

### See Also {#see-also}

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. Note, the state stored in other text annotation which has state and statemodel keys.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Status for assignment. |

### See Also {#see-also-1}

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)
