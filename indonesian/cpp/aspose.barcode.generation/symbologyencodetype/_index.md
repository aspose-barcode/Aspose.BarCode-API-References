---
title: "Kelas Aspose::BarCode::Generation::SymbologyEncodeType"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::Generation::SymbologyEncodeType. Tipe pengkodean simbolografi. Lihat EncodeTypes untuk mendapatkan instance dalam C++."
type: docs
weight: 4900
url: /id/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Tipe pengkodean simbolografi. Lihat [EncodeTypes](../encodetypes/) untuk mendapatkan instance.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseEncodeType](../baseencodetype/) yang ditentukan. |
| [get_Classification](../baseencodetype/get_classification/)() const | Mendapatkan klasifikasi simbolografi ini. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Mendapatkan indeks tipe pengkodean |
| [get_TypeName](../baseencodetype/get_typename/)() const | Mendapatkan nama tipe pengkodean |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [GetString](../baseencodetype/getstring/)() | Mengonversi instance [BaseEncodeType](../baseencodetype/) menjadi representasi string yang setara. Format stringnya: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Mengonversi instance [BaseEncodeType](../baseencodetype/) menjadi representasi string yang setara. Format stringnya: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Mengonversi representasi string dari nama [BaseEncodeType](../baseencodetype/) menjadi instance-nya. |
| [ToString](../baseencodetype/tostring/)() const override | Mengembalikan nama [BaseEncodeType](../baseencodetype/) yang diberikan sebagai string. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Mengonversi representasi string dari [BaseEncodeType](../baseencodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Mengonversi representasi string dari [BaseEncodeType](../baseencodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
## Catatan


Contoh ini menunjukkan cara mendapatkan instance dari kelas [SymbologyEncodeType](./).
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Lihat Juga

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
