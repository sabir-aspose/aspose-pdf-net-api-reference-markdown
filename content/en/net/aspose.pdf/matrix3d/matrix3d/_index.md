---
title: "Matrix3D.Matrix3D"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix3D constructor. Constructor creates standard 1 to 1 matrix A B C D E F G H I Tx Ty Tz 1 0 0 0 1 0 0 0 1 0 0 0"
type: docs
url: "/net/aspose.pdf/matrix3d/matrix3d/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix3d/matrix3d/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:01:06+00:00"
---
## Matrix3D() {#constructor}

Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Examples {#examples}

```csharp
Matrix3D m = new Matrix3D();
```

### See Also {#see-also}

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix3DArray | Double[] | Matrix data array. |

## Examples {#examples-1}

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### See Also {#see-also-1}

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Constructor accepts a matrix to create a copy

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D object. |

### See Also {#see-also-2}

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Initializes transformation matrix with specified coefficients.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parameter | Type | Description |
| --- | --- | --- |
| a | Double | A matrix value. |
| b | Double | B matrix value. |
| c | Double | C matrix value. |
| d | Double | D matrix value. |
| e | Double | E matrix value. |
| f | Double | F matrix value. |
| g | Double | G matrix value. |
| h | Double | H matrix value. |
| i | Double | I matrix value. |
| tx | Double | TX matrix value. |
| ty | Double | TY matrix value. |
| tz | Double | TZ matrix value. |

## Examples {#examples-2}

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### See Also {#see-also-3}

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
