---
title: "method"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。根据当前设置生成条形码图像（C++）。"
type: docs
weight: 800
url: /zh/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


在当前设置下生成条形码图像。

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

条形码图像。参见 [Bitmap](../)。
## 备注



此示例展示了如何创建并保存条形码图像。
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## 另见

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
