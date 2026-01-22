---
title: BaseGenerationParameters.RotationAngle
second_title: Aspose.BarCode for .NET API Reference
description: BaseGenerationParameters property. BarCode image rotation angle measured in degree e.g. RotationAngle  0 or RotationAngle  360 means no rotation. If RotationAngle NOT equal to 90 180 270 or 0 it may increase the difficulty for the scanner to read the image. Default value 0
type: docs
weight: 110
url: /net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```csharp
public float RotationAngle { get; set; }
```

## Examples

This sample shows how to create and save a BarCode image.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### See Also

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


