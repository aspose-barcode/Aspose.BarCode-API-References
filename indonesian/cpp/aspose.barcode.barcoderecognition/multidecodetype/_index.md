---
title: "Kelas Aspose::BarCode::BarCodeRecognition::MultiDecodeType"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::BarCodeRecognition::MultiDecodeType. Tipe decode komposit dalam C++."
type: docs
weight: 2600
url: /id/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Tipe decode komposit.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Menambahkan satu lagi [SingleDecodeType](../singledecodetype/) ke [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Periksa apakah ini berisi semua tipe dari tipe barcode. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Apakah mengandung salah satu tipe. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MultiDecodeType](./) yang ditentukan. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Mengembalikan nilai yang menunjukkan apakah koleksi tipe decode ini hanya berisi nilai [SingleDecodeType](../singledecodetype/) yang ditentukan. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MultiDecodeType](./) yang ditentukan. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../basedecodetype/) yang ditentukan. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Mengecualikan [SingleDecodeType](../singledecodetype/) dari [MultiDecodeType](./) dan mengembalikan instance [MultiDecodeType](./) yang baru. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Mengembalikan jumlah tipe tunggal. |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [GetSingleTypes](./getsingletypes/)() | Mewakili daftar tipe tunggal. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Menginisialisasi sebuah instance baru dari kelas [MultiDecodeType](./). |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi sebuah instance baru dari kelas [MultiDecodeType](./). |
| [ToString](./tostring/)() const override | Metode yang dioverride yang merepresentasikan [MultiDecodeType](./) sebagai string. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Mengonversi representasi string dari [MultiDecodeType](./) menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Mengonversi representasi string dari [SingleDecodeType](../singledecodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Mengonversi representasi string dari [BaseDecodeType](../basedecodetype/) ke instance-nya, setelah menentukan tipe konkret. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
## Catatan


Contoh ini menunjukkan cara membuat tipe MultiDecode komposit yang menggabungkan [SingleDecodeType](../singledecodetype/) dan tipe MultiDecode.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## Lihat Juga

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
