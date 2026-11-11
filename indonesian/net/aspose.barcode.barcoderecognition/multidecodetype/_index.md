---
title: "Kelas MultiDecodeType"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.BarCodeRecognition.MultiDecodeType. Tipe decode komposit"
type: docs
weight: 320
url: /id/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Tipe decode komposit.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Menginisialisasi sebuah instance baru dari kelas `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Menginisialisasi sebuah instance baru dari kelas `MultiDecodeType`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Mengembalikan sejumlah tipe tunggal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Menambahkan satu lagi [`SingleDecodeType`](../singledecodetype/) ke MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Periksa apakah ini berisi semua tipe dari tipe barcode. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Apakah mengandung salah satu tipe. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [`BaseDecodeType`](../basedecodetype/) yang ditentukan. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `MultiDecodeType` yang ditentukan. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `MultiDecodeType` yang ditentukan. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Mengembalikan nilai yang menunjukkan apakah koleksi tipe decode ini hanya berisi nilai [`SingleDecodeType`](../singledecodetype/) yang ditentukan. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Mengecualikan [`SingleDecodeType`](../singledecodetype/) dari MultiDecodeType dan mengembalikan instance MultiDecodeType baru. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Mewakili sebuah daftar tipe tunggal. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Metode yang dioverride yang merepresentasikan MultiDecodeType sebagai string. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Mengonversi representasi string dari MultiDecodeType menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |

## Contoh

Contoh ini menunjukkan cara membuat tipe MultiDecode gabungan yang menggabungkan SingleDecodeType dan tipe MultiDecode.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### Lihat Juga

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


