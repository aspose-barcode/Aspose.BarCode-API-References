---
title: "metode"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Mengembalikan hanya jenis barcode yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, barcode yang dikenali dari jenis lain yang kompatibel atau setara akan disaring. Nilai default adalah false di C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Mengembalikan hanya tipe barcode yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, barcode yang dikenali dengan tipe lain yang kompatibel atau setara akan disaring. Nilai default adalah false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Catatan


Contoh ini menunjukkan cara membatasi hasil pengenalan hanya pada jenis barcode yang diminta
```cpp
[C#]
//hasilkan barcode EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//kenali hanya barcode UPCA (tidak ada hasil, karena sumbernya EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//kenali tipe yang kompatibel: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 akan dikembalikan sebagai setara UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Mengembalikan hanya jenis barcode yang secara eksplisit ditentukan untuk pengenalan. Nilai default adalah false.
## Lihat Juga

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
