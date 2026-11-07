---
title: "Aspose::BarCode::Generation::DotCodeParameters class"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::DotCodeParameters class. Parameter DotCode dalam C++."
type: docs
weight: 2200
url: /id/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


Parameter DotCode.

```cpp
class DotCodeParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [get_Columns](./get_columns/)() const | Mengidentifikasi jumlah kolom. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah kolom harus minimal 5. Nilai default: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Mengidentifikasi encoding ECI. Digunakan ketika DotCodeEncodeMode diatur ke Auto. Nilai default: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Mengidentifikasi mode encode DotCode. Nilai default: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false. |
| [get_Rows](./get_rows/)() const | Mengidentifikasi jumlah baris. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah baris harus minimal 5. Nilai default: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Mengidentifikasi ID dari barcode mode structured append DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Mengidentifikasi jumlah barcode mode structured append DotCode. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [set_Columns](./set_columns/)(int32_t) | Mengidentifikasi jumlah kolom. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah kolom harus minimal 5. Nilai default: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Mengidentifikasi encoding ECI. Digunakan ketika DotCodeEncodeMode diatur ke Auto. Nilai default: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Mengidentifikasi mode encode DotCode. Nilai default: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false. |
| [set_Rows](./set_rows/)(int32_t) | Mengidentifikasi jumlah baris. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah baris harus minimal 5. Nilai default: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Mengidentifikasi ID dari barcode mode structured append DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Mengidentifikasi jumlah barcode mode structured append DotCode. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [DotCodeParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
