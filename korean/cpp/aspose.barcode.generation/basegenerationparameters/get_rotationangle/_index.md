---
title: "메서드"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. BarCode 이미지 회전 각도(도 단위)이며, 예를 들어 RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: C++에서 0."
type: docs
weight: 700
url: /ko/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## 비고


이 샘플은 [BarCode](../../../aspose.barcode/) 이미지를 생성하고 저장하는 방법을 보여줍니다.
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## 또 보기

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
