---
title: "metode"
linktitle: "set_RotationAngle"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. sudut rotasi gambar BarCode, diukur dalam derajat, misalnya RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270 atau 0, dapat meningkatkan kesulitan pemindai untuk membaca gambar. Nilai default: 0 dalam C++."
type: docs
weight: 800
url: /id/cpp/aspose.barcode.generation/basegenerationparameters/set_rotationangle/
---
## BaseGenerationParameters::set_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
void Aspose::BarCode::Generation::BaseGenerationParameters::set_RotationAngle(float value)
```

## Catatan


Contoh ini menunjukkan cara membuat dan menyimpan gambar [BarCode](../../../aspose.barcode/).
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## Lihat Juga

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
