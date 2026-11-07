---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Tipe komponen 2D dalam C++."
type: docs
weight: 8700
url: /id/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Tipe komponen 2D

```cpp
enum class TwoDComponentType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Pilih otomatis tipe komponen 2D |
| CC_A | 1 | Tipe CC-A komponen 2D. Ini adalah varian struktural dari MicroPDF417 |
| CC_B | 2 | Tipe CC-B komponen 2D. Ini adalah simbol MicroPDF417. |
| CC_C | 3 | Tipe CC-C komponen 2D. Ini adalah simbol PDF417. |

## Catatan


Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa teks kode 1D dan teks kode 2D dipisahkan oleh simbol '/'
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
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

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
