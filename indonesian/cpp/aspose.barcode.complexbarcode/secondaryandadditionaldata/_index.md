---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Kelas untuk menyimpan data sekunder dan tambahan HIBC LIC dalam C++."
type: docs
weight: 2600
url: /id/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Kelas untuk menyimpan data sekunder dan tambahan HIBC LIC.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [SecondaryAndAdditionalData](./) yang ditentukan. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Mengidentifikasi tanggal pembuatan. Tanggal pembuatan dapat diatur ke DateTime.MinValue agar tidak menggunakan bidang ini. Nilai default: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Mengidentifikasi tanggal kedaluwarsa. Akan digunakan jika ExpiryDateFormat tidak diatur ke None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Mengidentifikasi format tanggal kedaluwarsa. |
| [get_LotNumber](./get_lotnumber/)() const | Mengidentifikasi nomor lot atau batch. Nomor lot/batch harus berupa string alfanumerik dengan panjang hingga 18 simbol. . |
| [get_Quantity](./get_quantity/)() const | Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. Kuantitas dapat diatur ke -1 agar tidak menggunakan bidang ini. Nilai default: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Mengidentifikasi nomor seri. Nomor seri harus berupa string alfanumerik dengan panjang hingga 18 simbol. |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ParseFromString](./parsefromstring/)(System::String) | Membuat instance data tambahan sekunder dan tambahan dari format string sesuai spesifikasi HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Mengidentifikasi tanggal pembuatan. Tanggal pembuatan dapat diatur ke DateTime.MinValue agar tidak menggunakan bidang ini. Nilai default: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Mengidentifikasi tanggal kedaluwarsa. Akan digunakan jika ExpiryDateFormat tidak diatur ke None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Mengidentifikasi format tanggal kedaluwarsa. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Mengidentifikasi nomor lot atau batch. Nomor lot/batch harus berupa string alfanumerik dengan panjang hingga 18 simbol. . |
| [set_Quantity](./set_quantity/)(int32_t) | Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. Kuantitas dapat diatur ke -1 agar tidak menggunakan bidang ini. Nilai default: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Mengidentifikasi nomor seri. Nomor seri harus berupa string alfanumerik dengan panjang hingga 18 simbol. |
| [ToString](./tostring/)() const override | Mengonversi data ke format string sesuai spesifikasi HIBC LIC. |
## Lihat Juga

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
