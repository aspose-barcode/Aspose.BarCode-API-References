---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BaseGenerationParameters 属性。条形码图像的旋转角度，以度为单位，例如 RotationAngle 0 或 RotationAngle 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值 0"
type: docs
weight: 110
url: /zh/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

条形码图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。

```csharp
public float RotationAngle { get; set; }
```

## 示例

此示例展示如何创建并保存条形码图像。

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### 另见

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


