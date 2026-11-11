---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BaseGenerationParameters özelliği. BarCode görüntüsünün derece cinsinden döndürme açısı, ör. RotationAngle 0 veya RotationAngle 360 dönüş olmadığını gösterir. RotationAngle 90, 180, 270 veya 0 dışında bir değer ise tarayıcının görüntüyü okumasını zorlaştırabilir. Varsayılan değer 0"
type: docs
weight: 110
url: /tr/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode görüntüsü döndürme açısı, derece cinsinden ölçülür, ör. RotationAngle = 0 veya RotationAngle = 360 dönüş olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının görüntüyü okumasını zorlaştırabilir. Varsayılan değer: 0.

```csharp
public float RotationAngle { get; set; }
```

## Örnekler

Bu örnek, bir BarCode görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Ayrıca Bakınız

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


