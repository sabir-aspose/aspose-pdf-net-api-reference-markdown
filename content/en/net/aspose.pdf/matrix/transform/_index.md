---
title: "Matrix.Transform"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Transforms point using this matrix"
type: docs
url: "/net/aspose.pdf/matrix/transform/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix/transform/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:00:52+00:00"
---
## Transform(Point) {#transform}

Transforms point using this matrix.

```csharp
public Point Transform(Point p)
```

| Parameter | Type | Description |
| --- | --- | --- |
| p | Point | Point which will be transformed. |

### Return Value {#return-value}

Transformation result.

## Examples {#examples}

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### See Also {#see-also}

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Transforms coordinates using this matrix.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Double | X coordinate. |
| y | Double | Y coordinate. |
| x1 | Double& | Transformed X coordinate. |
| y1 | Double& | Transformed Y coordinate. |

## Examples {#examples-1}

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### See Also {#see-also-1}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transformes rectangle. If angle is not 90 * N degrees then bounding rectangle is returned.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Rectangle to be transformed. |

### Return Value {#return-value-1}

Transformed rectangle.

## Examples {#examples-2}

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### See Also {#see-also-2}

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
