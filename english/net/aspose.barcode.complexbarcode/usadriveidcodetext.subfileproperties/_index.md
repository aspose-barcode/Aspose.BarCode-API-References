---
title: Class USADriveIdCodetext.SubfileProperties
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties class. USA DL subfile properties offset and length are set automatically
type: docs
weight: 740
url: /net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

USA DL subfile properties, offset and length are set automatically.

```csharp
public class SubfileProperties
```

## Constructors

| Name | Description |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also be included in the length. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 2 byte type of subfile, like "DL" |

### See Also

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


