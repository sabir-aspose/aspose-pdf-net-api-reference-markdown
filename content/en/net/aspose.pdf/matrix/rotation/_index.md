---
title: "Matrix.Rotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Creates matrix for given rotation angle"
type: docs
url: "/net/aspose.pdf/matrix/rotation/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix/rotation/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:00:49+00:00"
---
## Rotation(double) {#rotation_1}

Creates matrix for given rotation angle.

```csharp
public static Matrix Rotation(double alpha)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alpha | Double | Rotation angle in radians. |

### Return Value {#return-value}

Transformation matrix.

## Examples {#examples}

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### See Also {#see-also}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Creates matrix for given rotation.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotation | Rotation | Rotation. Valid values are: None, on90, on180, on270 |

### Return Value {#return-value-1}

Matrix with rotation.

### See Also {#see-also-1}

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
