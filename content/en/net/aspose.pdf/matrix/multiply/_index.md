---
title: "Matrix.Multiply"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Multiplies the matrix by other matrix"
type: docs
url: "/net/aspose.pdf/matrix/multiply/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf/matrix/multiply/"
generated_from: "online-reference"
fetched_at: "2026-06-14T05:00:47+00:00"
---
## Matrix.Multiply method {#matrixmultiply-method}

Multiplies the matrix by other matrix.

```csharp
public Matrix Multiply(Matrix other)
```

| Parameter | Type | Description |
| --- | --- | --- |
| other | Matrix | Multiplier matrix. |

### Return Value {#return-value}

Result of multiplication.

## Examples {#examples}

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### See Also {#see-also}

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)
