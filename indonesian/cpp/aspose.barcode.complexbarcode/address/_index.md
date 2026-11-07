---
title: "kelas Aspose::BarCode::ComplexBarcode::Address"
linktitle: "Alamat"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "kelas Aspose::BarCode::ComplexBarcode::Address. Alamat kreditur atau debitur dalam C++."
type: docs
weight: 100
url: /id/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Address](./address/)() | Membuat instance dari [Address](./) |
| [Clear](./clear/)() | Menghapus semua bidang dan mengatur tipe menjadi [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Menentukan apakah objek yang ditentukan sama dengan objek saat ini. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Menentukan apakah alamat yang ditentukan sama dengan alamat saat ini. |
| [get_AddressLine1](./get_addressline1/)() const | Mendapatkan baris alamat 1. |
| [get_AddressLine2](./get_addressline2/)() const | Mendapatkan baris alamat 2. |
| [get_CountryCode](./get_countrycode/)() const | Mendapatkan kode negara ISO dua huruf. |
| [get_HouseNo](./get_houseno/)() const | Mendapatkan nomor rumah. |
| [get_Name](./get_name/)() const | Mendapatkan nama, baik nama depan dan belakang orang alami maupun nama perusahaan orang hukum. |
| [get_PostalCode](./get_postalcode/)() const | Mendapatkan kode pos. |
| [get_Street](./get_street/)() const | Mendapatkan jalan. |
| [get_Town](./get_town/)() const | Mendapatkan kota atau kota. |
| [get_Type](./get_type/)() const | Mendapatkan tipe alamat. |
| [GetHashCode](./gethashcode/)() const override | Mendapatkan kode hash untuk instance ini. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Mengatur baris alamat 1. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Mengatur baris alamat 2. |
| [set_CountryCode](./set_countrycode/)(System::String) | Mengatur kode negara ISO dua huruf. |
| [set_HouseNo](./set_houseno/)(System::String) | Mengatur nomor rumah. |
| [set_Name](./set_name/)(System::String) | Mengatur nama, baik nama depan dan belakang orang alami maupun nama perusahaan orang hukum. |
| [set_PostalCode](./set_postalcode/)(System::String) | Mengatur kode pos. |
| [set_Street](./set_street/)(System::String) | Mengatur jalan. |
| [set_Town](./set_town/)(System::String) | Mengatur kota atau daerah. |
## Catatan


Anda dapat mengatur jalan, nomor rumah, kode pos, dan kota (tipe *structured address*) atau baris alamat 1 dan 2 (tipe *combined address elements*). Tipe secara otomatis diatur setelah salah satu bidang ini diatur. Sebelum mengatur bidang, tipe alamat adalah *undetermined*. Jika bidang dari kedua tipe diatur, tipe alamat menjadi *conflicting*. Nama dan kode negara harus selalu diatur kecuali semua bidang kosong.
## Lihat Juga

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
