---
title: "Kelas Aspose::BarCode::BarCodeRecognition::BaseDecodeType"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::BarCodeRecognition::BaseDecodeType. Kelas dasar untuk MultiDecodeType dan SingleDecodeType dalam C++."
type: docs
weight: 900
url: /id/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Kelas dasar untuk [MultiDecodeType](../multidecodetype/) dan [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menentukan apakah salah satu tipe decode yang diberikan termasuk ke dalam |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [SingleDecodeType](../singledecodetype/) yang ditentukan. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MultiDecodeType](../multidecodetype/) yang ditentukan. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](./) yang ditentukan. |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Mengonversi representasi string dari [SingleDecodeType](../singledecodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Mengonversi representasi string dari [MultiDecodeType](../multidecodetype/) ke instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Mengonversi representasi string dari [BaseDecodeType](./) menjadi instance-nya, setelah menentukan tipe konkret. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
## Catatan


Contoh ini menunjukkan cara menggunakan [BaseDecodeType](./) dengan [SingleDecodeType](../singledecodetype/) dan [MultiDecodeType](../multidecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
