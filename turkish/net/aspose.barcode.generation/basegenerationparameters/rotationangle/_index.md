---
title: RotationAngle
second_title: Aspose.BarCode for .NET API Referansı
description: BarCode görüntü döndürme açısı derece cinsinden ölçülür örneğin Dönme Açısı  0 veya DönmeAçısı  360 döndürme olmadığı anlamına gelir. Döndürme Açısı 90 180 270 veya 0a eşit DEĞİLSE tarayıcının görüntüyü okuma zorluğunu artırabilir. Varsayılan değer 0.
type: docs
weight: 100
url: /tr/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode görüntü döndürme açısı, derece cinsinden ölçülür, örneğin Dönme Açısı = 0 veya DönmeAçısı = 360, döndürme olmadığı anlamına gelir. Döndürme Açısı 90, 180, 270 veya 0'a eşit DEĞİLSE, tarayıcının görüntüyü okuma zorluğunu artırabilir. Varsayılan değer: 0.

```csharp
public float RotationAngle { get; set; }
```

### Örnekler

Bu örnek, bir BarCode görüntüsünün nasıl oluşturulacağını ve kaydedileceğini gösterir.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Ayrıca bakınız

* class [BaseGenerationParameters](../../basegenerationparameters)
* ad alanı [Aspose.BarCode.Generation](../../basegenerationparameters)
* toplantı [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->