---
title: "类 ComplexBarcodeGenerator"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator 类。用于后端复杂条码（例如 SwissQR 图像生成）的 ComplexBarcodeGenerator"
type: docs
weight: 510
url: /zh/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator 用于后端复杂条码（例如 SwissQR）图像生成。

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | 创建 ComplexBarcodeGenerator 的实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | 生成参数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | 根据当前设置生成复杂条码图像。 |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | 根据当前设置生成并保存复杂条码图像。 |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | 根据当前设置生成并保存复杂条码图像。 |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | 根据当前设置生成并保存复杂条码图像。 |

## 示例

此示例展示了如何创建和保存 SwissQR 图像。

```csharp
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

### 另见

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


