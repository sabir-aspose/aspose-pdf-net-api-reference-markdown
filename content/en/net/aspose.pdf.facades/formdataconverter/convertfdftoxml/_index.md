---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormDataConverter method. Convert FDF file into XML"
type: docs
url: "/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/"
source_url: "https://reference.aspose.com/pdf/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/"
generated_from: "online-reference"
fetched_at: "2026-06-14T04:13:07+00:00"
---
## FormDataConverter.ConvertFdfToXml method {#formdataconverterconvertfdftoxml-method}

Convert FDF file into XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFdf | Stream | Stream which contains FDF to convert. |
| destXml | Stream | Source where reuslt XML will be placed. |

## Examples {#examples}

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### See Also {#see-also}

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
