---
title: "Matrix.Matrix"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix constructor. Constructor creates stanrard 1 to 1 matrix A B C D E F 1 0 0 1 0 0"
type: docs
url: "/net/aspose.pdf/matrix/matrix/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix/matrix/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:00:46+00:00"
---
## Matrix() {#constructor}

Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Examples {#examples}

```csharp
Matrix m = new Matrix();
```

### See Also {#see-also}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Constructor accepts a matrix with following array representation: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | Double[] | Matrix data array. |

## Examples {#examples-1}

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### See Also {#see-also-1}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Constructor accepts a matrix with following array representation: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | Single[] | Matrix data array. |

### See Also {#see-also-2}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Constructor accepts a matrix to create a copy

```csharp
public Matrix(Matrix matrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | Matrix | Matrix object. |

### See Also {#see-also-3}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Initializes transformation matrix with specified coefficients.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parameter | Type | Description |
| --- | --- | --- |
| a | Double | A matrix value. |
| b | Double | B matrix value. |
| c | Double | C matrix value. |
| d | Double | D matrix value. |
| e | Double | E matrix value. |
| f | Double | F matrix value. |

## Examples {#examples-2}

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### See Also {#see-also-4}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
