---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator فئة"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator فئة. ComplexBarcodeGenerator لتوليد صور الباركود المعقد في الخلفية (مثل SwissQR) في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | ينشئ مثيلة من [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | نظّف أي موارد قيد الاستخدام. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | ينشئ صورة باركود معقدة وفقًا للإعدادات الحالية. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) المعلمات. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | ينشئ ويحفظ صورة باركود معقدة وفقًا للإعدادات الحالية. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | ينشئ ويحفظ صورة باركود معقدة وفقًا للإعدادات الحالية. |
| [Save](./save/)(System::String) | ينشئ ويحفظ صورة باركود معقدة وفقًا للإعدادات الحالية. |
## ملاحظات


يعرض هذا المثال كيفية إنشاء وحفظ صورة SwissQR.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // تهيئة باقي الحقول
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## انظر أيضًا

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
