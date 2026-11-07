---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class. ComplexBarcodeGenerator для генерации изображений сложных штрихкодов (например, SwissQR) на C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Описание |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Создаёт экземпляр [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Освободить любые используемые ресурсы. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Создаёт изображение сложного штрихкода с текущими настройками. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) параметры. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Создаёт и сохраняет изображение сложного штрихкода с текущими настройками. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Создаёт и сохраняет изображение сложного штрихкода с текущими настройками. |
| [Save](./save/)(System::String) | Создаёт и сохраняет изображение сложного штрихкода с текущими настройками. |
## Примечания


Этот пример показывает, как создать и сохранить изображение SwissQR.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // инициализировать остальные поля
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
