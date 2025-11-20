---
title: Class DataMatrixParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.DataMatrixParameters class. DataMatrix parameters
type: docs
weight: 1120
url: /net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

DataMatrix parameters.

```csharp
public class DataMatrixParameters
```

## Properties

| Name | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | Height/Width ratio of 2D BarCode module. |
| [Columns](../../aspose.barcode.generation/datamatrixparameters/columns/) { get; set; } | Columns count. |
| [DataMatrixEcc](../../aspose.barcode.generation/datamatrixparameters/datamatrixecc/) { get; set; } | Gets or sets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200. |
| [DataMatrixEncodeMode](../../aspose.barcode.generation/datamatrixparameters/datamatrixencodemode/) { get; set; } | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.Auto. |
| [DataMatrixVersion](../../aspose.barcode.generation/datamatrixparameters/datamatrixversion/) { get; set; } | Gets or sets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto. |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | Gets or sets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1 |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes.GS1DataMatrix Default value: MacroCharacters.None. |
| [Rows](../../aspose.barcode.generation/datamatrixparameters/rows/) { get; set; } | Rows count. |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | File ID for Structured Append mode of Datamatrix barcode. Default value: 0 |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | Returns a human-readable string representation of this `DataMatrixParameters`. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


