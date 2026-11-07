---
title: "メソッド"
linktitle: "set_RotationAngle"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。 BarCode 画像の回転角度（度単位）。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。RotationAngle が 90、180、270、または 0 以外の場合、スキャナーが画像を読み取る難易度が上がる可能性があります。デフォルト値: 0（C++）。"
type: docs
weight: 800
url: /ja/cpp/aspose.barcode.generation/basegenerationparameters/set_rotationangle/
---
## BaseGenerationParameters::set_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
void Aspose::BarCode::Generation::BaseGenerationParameters::set_RotationAngle(float value)
```

## 備考


このサンプルは、[BarCode](../../../aspose.barcode/) 画像を作成して保存する方法を示しています。
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## 関連項目

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
