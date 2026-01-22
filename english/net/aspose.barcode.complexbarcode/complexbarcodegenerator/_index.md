---
title: Class ComplexBarcodeGenerator
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator class. ComplexBarcodeGenerator for backend complex barcode e.g. SwissQR images generation
type: docs
weight: 440
url: /net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation.

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## Constructors

| Name | Description |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | Creates an instance of ComplexBarcodeGenerator. |

## Properties

| Name | Description |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | Generation parameters. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | Generates complex barcode image under current settings. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | Generates and saves complex barcode image under current settings. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Generates and saves complex barcode image under current settings. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Generates and saves complex barcode image under current settings. |

## Examples

This sample shows how to create and save a SwissQR image.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // init rest of the fields
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### See Also

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


