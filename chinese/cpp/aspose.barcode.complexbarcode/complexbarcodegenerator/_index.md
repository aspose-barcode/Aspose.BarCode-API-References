---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator 类。ComplexBarcodeGenerator 用于在 C++ 中生成后端复杂条码（例如 SwissQR）图像。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | 创建 [ComplexBarcodeGenerator](./) 的实例。 |
| [Dispose](./dispose/)() override | 清理正在使用的任何资源。 |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | 根据当前设置生成复杂条码图像。 |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) 参数。 |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | 根据当前设置生成并保存复杂条码图像。 |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | 根据当前设置生成并保存复杂条码图像。 |
| [Save](./save/)(System::String) | 根据当前设置生成并保存复杂条码图像。 |
## 备注


此示例展示了如何创建并保存 SwissQR 图像。
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // 初始化其余字段
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
