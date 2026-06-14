---
title: "Artifact.BeginUpdates"
second_title: "Aspose.PDF for .NET API Reference"
description: "Artifact method. Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once"
type: docs
url: "/net/aspose.pdf/artifact/beginupdates/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/artifact/beginupdates/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:48:21+00:00"
---
## Artifact.BeginUpdates method {#artifactbeginupdates-method}

Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once.

```csharp
public void BeginUpdates()
```

## Examples {#examples}

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### See Also {#see-also}

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
