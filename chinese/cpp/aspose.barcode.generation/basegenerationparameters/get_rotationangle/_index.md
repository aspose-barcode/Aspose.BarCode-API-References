---
title: "method"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。条形码图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0（C++）。"
type: docs
weight: 700
url: /zh/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## 备注


此示例展示了如何创建并保存 [BarCode](../../../aspose.barcode/) 图像。
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## 另见

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
