---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Mode pengkodean untuk barcode Code128. Spesifikasi Code 128 dalam C++."
type: docs
weight: 5900
url: /id/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Mode enkoding untuk kode batang Code128. Code 128

spesifikasi.

```cpp
enum class Code128EncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Enkode teks kode dalam mode klasik ISO 15417. Mode ini harus digunakan dalam semua kasus biasa. |
| CodeA | 1 | Enkode teks kode hanya dalam kumpulan kode 128A. |
| CodeB | 2 | Enkode teks kode hanya dalam kumpulan kode 128B. |
| CodeC | 4 | Enkode teks kode hanya dalam kumpulan kode 128C. |
| CodeAB | 3 | Enkode teks kode hanya dalam kumpulan kode 128A dan 128B. |
| CodeAC | 5 | Enkode teks kode hanya dalam kumpulan kode 128A dan 128C. |
| CodeBC | 6 | Enkode teks kode hanya dalam kumpulan kode 128B dan 128C. |

## Catatan


Kode ini menunjukkan cara menghasilkan kode 128 dengan enkoding yang berbeda.
```cpp
[C#]
//Hasilkan kode 128 dengan enkoding ISO 15417.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Hasilkan kode 128 hanya dengan enkoding KodeSet A.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
