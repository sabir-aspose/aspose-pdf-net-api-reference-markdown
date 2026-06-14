---
title: "Class VectorStoreListQueryParameters"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.VectorStoreListQueryParameters class. Query parameters object for listing vector stores"
type: docs
url: "/net/aspose.pdf.ai/vectorstorelistqueryparameters/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/vectorstorelistqueryparameters/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:58:49+00:00"
---
## VectorStoreListQueryParameters class {#vectorstorelistqueryparameters-class}

Query parameters object for listing vector stores.

```csharp
public class VectorStoreListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [VectorStoreListQueryParameters](vectorstorelistqueryparameters/)() | The default constructor. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Gets or sets a cursor for use in pagination. after is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include after=obj_foo in order to fetch the next page of the list. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Gets or sets a cursor for use in pagination. before is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include before=obj_foo in order to fetch the previous page of the list. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Gets or sets a limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Gets or sets sort order by the created_at timestamp of the objects. asc for ascending order and desc for descending order. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorelistqueryparameters/getqueryparameters/)() | Gets the query parameters for listing vector stores. |

### See Also {#see-also}

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)
