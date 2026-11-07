---
title: "method"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Угол поворота изображения BarCode, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие вращения. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0 в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## Примечания


Этот пример показывает, как создать и сохранить изображение [BarCode](../../../aspose.barcode/).
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## См. также

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
