---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarcodeGenerator 方法。根据当前设置生成条形码图像"
type: docs
weight: 80
url: /zh/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

根据当前设置生成条形码图像。

```csharp
public Bitmap GenerateBarCodeImage()
```

### 返回值

条码图像。参见 Bitmap。

## 示例

此示例展示了如何创建并保存条形码图像。

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### 另见

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


