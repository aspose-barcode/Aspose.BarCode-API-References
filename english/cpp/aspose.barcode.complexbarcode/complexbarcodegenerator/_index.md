---
title: Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class
linktitle: ComplexBarcodeGenerator
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class. ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation in C++.'
type: docs
weight: 300
url: /cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Creates an instance of [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Clean up any resources being used. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Generates complex barcode image under current settings. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) parameters. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Aspose::BarCode::Generation::BarCodeImageFormat) | Generates and saves complex barcode image under current settings. |
| [Save](./save/)(System::String, Aspose::BarCode::Generation::BarCodeImageFormat) | Generates and saves complex barcode image under current settings. |
| [Save](./save/)(System::String) | Generates and saves complex barcode image under current settings. |
## Remarks


This sample shows how to create and save a SwissQR image. 
```cpp
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

## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
