---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 3900
url: /id/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | 0 | Menonaktifkan pengenalan tambahan barcode pada gambar terbalik untuk semua jenis barcode kecuali [QR](../../aspose.barcode.barcoderecognition.qr/) Code. |
| Dinonaktifkan | 1 | Menonaktifkan pengenalan tambahan barcode pada gambar terbalik. |
| Diaktifkan | 2 | Mengaktifkan pengenalan tambahan barcode pada gambar terbalik |

## Catatan


Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang pada gambar dengan warna terbalik (luminansi).

Contoh ini menunjukkan cara menggunakan mode InverseImage
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
