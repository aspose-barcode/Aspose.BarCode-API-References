---
title: "metode"
linktitle: "get_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Parameter GS1 Composite Bar dalam C++."
type: docs
weight: 2500
url: /id/cpp/aspose.barcode.generation/barcodeparameters/get_gs1compositebar/
---
## BarcodeParameters::get_GS1CompositeBar method


Parameter GS1 Composite Bar.

```cpp
System::SharedPtr<GS1CompositeBarParameters> Aspose::BarCode::Generation::BarcodeParameters::get_GS1CompositeBar() const
```

## Catatan


Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Catatan bahwa teks kode 1D dan teks kode 2D dipisahkan oleh simbol '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // Rasio aspek komponen 2D
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // Dimensi X komponen 1D dan 2D
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // Tinggi komponen 1D
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## Lihat Juga

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
