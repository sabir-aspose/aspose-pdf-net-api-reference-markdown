---
title: "Matrix.GetAngle"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Transaltes rotation into angle degrees"
type: docs
url: "/net/aspose.pdf/matrix/getangle/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix/getangle/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:00:43+00:00"
---
## Matrix.GetAngle method {#matrixgetangle-method}

Transaltes rotation into angle (degrees)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotation | Rotation | Rotation value. |

### Return Value {#return-value}

Angle value.

## Examples {#examples}

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### See Also {#see-also}

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
