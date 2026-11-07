---
title: "metode"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Hasilkan gambar barcode dengan pengaturan saat ini di C++."
type: docs
weight: 800
url: /id/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Hasilkan gambar barcode dengan pengaturan saat ini.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Gambar barcode. Lihat [Bitmap](../).
## Catatan



Contoh ini menunjukkan cara membuat dan menyimpan gambar barcode.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Lihat Juga

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
