---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 3600
url: /id/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| High | 0 | Mengaktifkan metode pengenalan untuk barcode kualitas tinggi. |
| Normal | 1 | Mengaktifkan metode pengenalan untuk barcode kualitas Umum (Normal). |
| Low | 2 | Mengaktifkan metode pengenalan untuk barcode kualitas rendah. |

## Catatan


Mode yang memungkinkan metode mengenali elemen kode batang dengan kualitas yang dipilih. Elemen kode batang dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat pengenalan.

Contoh ini menunjukkan cara menggunakan mode BarcodeQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
