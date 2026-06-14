---
title: "DocumentChunk.GetVectorDefinition"
second_title: "Aspose.PDF for .NET API Reference"
description: "DocumentChunk method. Returns a VectorStoreCollectionDefinition describing the schema of DocumentChunk for use with a vector store collection"
type: docs
url: "/net/aspose.pdf.ai/documentchunk/getvectordefinition/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/documentchunk/getvectordefinition/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:49:34+00:00"
---
## DocumentChunk.GetVectorDefinition method {#documentchunkgetvectordefinition-method}

Returns a VectorStoreCollectionDefinition describing the schema of [`DocumentChunk`](../) for use with a vector store collection.

```csharp
public static VectorStoreCollectionDefinition GetVectorDefinition(int dimensions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dimensions | Int32 | The number of dimensions of the embedding vector produced by the embedding model. |

### Return Value {#return-value}

A VectorStoreCollectionDefinition that maps all relevant [`DocumentChunk`](../) properties to their vector store roles.

### Exceptions {#exceptions}

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when *dimensions* is less than or equal to zero. |

### See Also {#see-also}

* class [DocumentChunk](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
