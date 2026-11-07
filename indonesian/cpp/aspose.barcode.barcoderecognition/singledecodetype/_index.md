---
title: "Kelas Aspose::BarCode::BarCodeRecognition::SingleDecodeType"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::BarCodeRecognition::SingleDecodeType. Tipe decode tunggal. Lihat tipe decode untuk mendapatkan instance dalam C++."
type: docs
weight: 3200
url: /id/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Tipe decode tunggal. Lihat tipe decode untuk mendapatkan instance.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Mengembalikan nilai yang menunjukkan apakah instance ini termasuk dalam daftar yang ditentukan. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [SingleDecodeType](./) yang ditentukan. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Mengembalikan nilai yang menunjukkan apakah koleksi [MultiDecodeType](../multidecodetype/) yang ditentukan hanya berisi tipe decode ini. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [SingleDecodeType](./) yang ditentukan. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../basedecodetype/) yang ditentukan. |
| [get_TypeIndex](./get_typeindex/)() const | Mendapatkan indeks tipe decode |
| [get_TypeName](./get_typename/)() const | Mendapatkan nama tipe decode |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [GetString](./getstring/)() | Mengonversi instance [SingleDecodeType](./) ke representasi string yang setara. Format stringnya adalah: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Mengonversi instance [SingleDecodeType](./) ke representasi string yang setara. Format stringnya adalah: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Mengonversi representasi string dari nama [SingleDecodeType](./) ke instance-nya. |
| [ToString](./tostring/)() const override | Mengembalikan nama [SingleDecodeType](./) yang diberikan sebagai string. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Mengonversi representasi string dari [SingleDecodeType](./) ke instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Mengonversi representasi string dari [MultiDecodeType](../multidecodetype/) ke instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Mengonversi representasi string dari [BaseDecodeType](../basedecodetype/) ke instance-nya, setelah menentukan tipe konkret. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
## Catatan


Contoh ini menunjukkan cara mendapatkan instance tipe decode tunggal.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Lihat Juga

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
