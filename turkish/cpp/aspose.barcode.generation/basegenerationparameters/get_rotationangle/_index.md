---
title: "metot"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. BarCode görüntüsünün derece cinsinden döndürme açısı, ör. RotationAngle = 0 veya RotationAngle = 360 döndürme olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının görüntüyü okumasını zorlaştırabilir. Varsayılan değer: 0 C++'ta."
type: docs
weight: 700
url: /tr/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## Açıklamalar


Bu örnek, bir [BarCode](../../../aspose.barcode/) görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## Ayrıca Bakınız

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
