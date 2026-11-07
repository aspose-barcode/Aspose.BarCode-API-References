---
title: "metode"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Membersihkan nilai string agar sesuai dengan Swiss Payment Standards 2018 dalam C++."
type: docs
weight: 100
url: /id/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Membersihkan nilai string agar dapat digunakan untuk Standar Pembayaran Swiss 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | System::String | Nilai string yang akan dibersihkan. |
| result | Payments::CleaningResult\& | Hasil yang akan diisi dengan string yang telah dibersihkan dan flag. |
## Catatan


Karakter yang tidak didukung (menurut Swiss Payment Standards 2018, bab 2.4.1 dan lampiran D) diganti dengan spasi (whitespace yang tidak didukung) atau titik (semua karakter tidak didukung lainnya). Spasi di awal dan akhir dihapus.

Jika karakter di atas 0xff terdeteksi, string pertama-tama dinormalisasi sehingga huruf dengan umlaut atau aksen yang diekspresikan dengan dua kode poin digabung menjadi satu kode poin (jika memungkinkan), beberapa di antaranya mungkin menjadi valid.

Jika string yang dihasilkan seluruhnya spasi, **null** dikembalikan.

## Lihat Juga

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
