---
title: "Matrix3D.GetAngle"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix3D method. Translates rotation into angle degrees"
type: docs
url: "/net/aspose.pdf/matrix3d/getangle/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix3d/getangle/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:01:03+00:00"
---
## Matrix3D.GetAngle method {#matrix3dgetangle-method}

Translates rotation into angle (degrees)

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
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
