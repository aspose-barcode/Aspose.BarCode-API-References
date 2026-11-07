---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 4000
url: /id/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Nilai XDimension terdeteksi oleh AI (SVM). Pada saat ini sama dengan Normal |
| Kecil | 1 | Mendeteksi kode batang dengan XDimension kecil dalam 1 piksel atau lebih dengan kualitas dari BarcodeQuality |
| Normal | 2 | Mendeteksi kode batang dengan XDimension klasik dalam 2 piksel atau lebih dengan kualitas dari BarcodeQuality atau kode batang berkualitas tinggi. |
| Besar | 3 | Mendeteksi kode batang dengan XDimension besar dengan kualitas dari BarcodeQuality yang diambil dengan kamera resolusi tinggi. |
| UseMinimalXDimension | 4 | Mendeteksi barcode dari ukuran yang ditetapkan dalam MinimalXDimension dengan kualitas dari BarcodeQuality |

## Catatan


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Contoh ini menunjukkan cara menggunakan mode XDimension
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
