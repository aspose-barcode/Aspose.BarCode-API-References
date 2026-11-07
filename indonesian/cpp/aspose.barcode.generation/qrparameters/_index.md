---
title: "Aspose::BarCode::Generation::QrParameters class"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::Generation::QrParameters. Parameter QR dalam C++."
type: docs
weight: 4400
url: /id/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


Parameter QR.

```cpp
class QrParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [get_ECIEncoding](./get_eciencoding/)() const | Identifier Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | Tipe simbolologi QR dari mode pengkodean [BarCode](../../aspose.barcode/). Nilai default: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Tingkat koreksi kesalahan Reed-Solomon untuk kode batang QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | Parameter penambahan terstruktur QR. Mode penambahan terstruktur tidak didukung oleh kode batang MicroQR dan RectMicroQR. |
| [get_Version](./get_version/)() const | Versi QR Code. Dari Versi1 hingga Versi40. Nilai default adalah [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identifier Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | Tipe simbolologi QR dari mode pengkodean [BarCode](../../aspose.barcode/). Nilai default: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Tingkat koreksi kesalahan Reed-Solomon untuk kode batang QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | Parameter penambahan terstruktur QR. Mode penambahan terstruktur tidak didukung oleh kode batang MicroQR dan RectMicroQR. |
| [set_Version](./set_version/)(QRVersion) | Versi QR Code. Dari Versi1 hingga Versi40. Nilai default adalah [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [QrParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
