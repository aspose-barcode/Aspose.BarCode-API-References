---
title: Class DotCodeParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.DotCodeParameters class. DotCode parameters
type: docs
weight: 1160
url: /net/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class

DotCode parameters.

```csharp
public class DotCodeParameters
```

## Properties

| Name | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/dotcodeparameters/aspectratio/) { get; set; } | Height/Width ratio of 2D BarCode module. |
| [Columns](../../aspose.barcode.generation/dotcodeparameters/columns/) { get; set; } | Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1 |
| [DotCodeEncodeMode](../../aspose.barcode.generation/dotcodeparameters/dotcodeencodemode/) { get; set; } | Identifies DotCode encode mode. Default value: Auto. |
| [DotCodeStructuredAppendModeBarcodeId](../../aspose.barcode.generation/dotcodeparameters/dotcodestructuredappendmodebarcodeid/) { get; set; } | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [DotCodeStructuredAppendModeBarcodesCount](../../aspose.barcode.generation/dotcodeparameters/dotcodestructuredappendmodebarcodescount/) { get; set; } | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [ECIEncoding](../../aspose.barcode.generation/dotcodeparameters/eciencoding/) { get; set; } | Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [IsReaderInitialization](../../aspose.barcode.generation/dotcodeparameters/isreaderinitialization/) { get; set; } | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [Rows](../../aspose.barcode.generation/dotcodeparameters/rows/) { get; set; } | Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1 |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/dotcodeparameters/tostring/)() | Returns a human-readable string representation of this `DotCodeParameters`. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


