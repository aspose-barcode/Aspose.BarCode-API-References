---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 3700
url: /id/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Saat ini sama dengan Disabled. Menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |
| Dinonaktifkan | 1 | Menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |
| Diaktifkan | 2 | Mengaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |

## Catatan


Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna.

Contoh ini menunjukkan cara menggunakan mode ComplexBackground
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
