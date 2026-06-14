---
title: "Class VectorStoreFileBatchFileListQueryParameters"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters class. Query parameters object for listing vector store file batch files"
type: docs
url: "/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/"
generated_from: "online-reference"
fetched_at: "2026-06-14T03:58:24+00:00"
---
## VectorStoreFileBatchFileListQueryParameters class {#vectorstorefilebatchfilelistqueryparameters-class}

Query parameters object for listing vector store file batch files.

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors {#constructors}

| Name | Description |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | The default constructor. |

## Properties {#properties}

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Gets or sets a cursor for use in pagination. after is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include after=obj_foo in order to fetch the next page of the list. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Gets or sets a cursor for use in pagination. before is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with obj_foo, your subsequent call can include before=obj_foo in order to fetch the previous page of the list. |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | Gets or sets a filter by file status. One of in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Gets or sets a limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Gets or sets sort order by the created_at timestamp of the objects. asc for ascending order and desc for descending order. |

## Methods {#methods}

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | Gets the query parameters for listing store file batch files. |

### See Also {#see-also}

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)
