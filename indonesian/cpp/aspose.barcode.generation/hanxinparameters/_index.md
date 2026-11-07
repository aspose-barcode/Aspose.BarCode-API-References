---
title: "Aspose::BarCode::Generation::HanXinParameters kelas"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::HanXinParameters kelas. Parameter Han Xin dalam C++."
type: docs
weight: 2900
url: /id/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Parameter Han Xin.

```cpp
class HanXinParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Identifier Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini berisi semua enkoding set karakter yang dikenal. |
| [get_EncodeMode](./get_encodemode/)() const | Mode enkoding HanXin. Nilai default: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Tingkat koreksi kesalahan Reed-Solomon untuk kode batang Han Xin. Dari rendah ke tinggi: L1, L2, L3, L4. lihat ErrorLevel. |
| [get_Version](./get_version/)() const | Versi Kode HanXin. Dari Version01 hingga Version84 untuk kode Han Xin. Nilai default adalah [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identifier Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini berisi semua enkoding set karakter yang dikenal. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | Mode enkoding HanXin. Nilai default: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Tingkat koreksi kesalahan Reed-Solomon untuk kode batang Han Xin. Dari rendah ke tinggi: L1, L2, L3, L4. lihat ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | Versi Kode HanXin. Dari Version01 hingga Version84 untuk kode Han Xin. Nilai default adalah [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [HanXinParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
