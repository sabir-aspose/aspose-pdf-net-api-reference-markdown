---
title: "Matrix.Scale"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Scales x and y with the matrix using the following formula x1 Ax Cy y1 Bx Dy"
type: docs
url: "/net/aspose.pdf/matrix/scale/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix/scale/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:00:49+00:00"
---
## Scale(double, double, out double, out double) {#scaledoubledoubleoutdoubleoutdouble}

Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Double | Input X coordinate |
| y | Double | Input Y coordinate |
| x1 | Double& | Output X coordinate |
| y1 | Double& | Output Y coordinate |

### See Also {#see-also}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix) {#scaledoubledoublematrix}

Applies scaling to the given matrix.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sx | Double | The scaling factor for the X-axis. |
| sy | Double | The scaling factor for the Y-axis. |
| source | Matrix | The matrix to scale. |

### Return Value {#return-value}

A new matrix that is the result of scaling the source matrix.

### See Also {#see-also-1}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
