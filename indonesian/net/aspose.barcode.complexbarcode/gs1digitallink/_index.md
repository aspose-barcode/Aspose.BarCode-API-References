---
title: "Kelas GS1DigitalLink"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.ComplexBarcode.GS1DigitalLink. Mewakili teks kode GS1 Digital Link untuk penyandian dan penguraian sebagai urutan berurutan elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan. Teks kode yang dibangun adalah URI GS1 Digital Link yang tidak terkompresi. Parameter kueri NonGS1 dan fragmen URI diabaikan saat parsing."
type: docs
weight: 540
url: /id/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Mewakili teks kode GS1 Digital Link untuk penyandian dan penguraian sebagai urutan berurutan elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan. Teks kode yang dibangun adalah URI GS1 Digital Link yang tidak terkompresi. Parameter kueri Non-GS1 dan fragmen URI diabaikan saat parsing.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Menginisialisasi GS1 Digital Link kosong dengan batang URI yang ditentukan. Kunci utama dipilih secara otomatis ketika tepat satu kandidat kunci utama hadir. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Menginisialisasi GS1 Digital Link kosong dengan batang URI yang ditentukan dan kunci utama. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Mendapatkan atau mengatur jenis barcode yang digunakan untuk menyandikan GS1 Digital Link ini. Jenis yang didukung adalah QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF, dan Code128. Nilai default adalah QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Mendapatkan jumlah elemen Identifier Aplikasi. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Mendapatkan salinan semua elemen dalam urutan sumber. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Mendapatkan sebuah elemen berdasarkan posisinya dalam urutan berurutan. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Mendapatkan Identifier Aplikasi yang digunakan sebagai kunci utama Digital Link. Null berarti kunci utama dipilih secara otomatis saat URI dibangun. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Mendapatkan awalan URI absolut sebelum segmen jalur kunci utama GS1. Batang tidak mengandung string kueri atau fragmen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Membuat GS1 Digital Link dengan menyalin semua elemen dari teks kode GS1 dan memilih satu-satunya kunci utama yang tersedia. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Membuat GS1 Digital Link dengan menyalin semua elemen dari teks kode GS1 dan menggunakan kunci utama yang ditentukan. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Menganalisis URI GS1 Digital Link yang tidak terkompresi. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Menambahkan elemen Identifier Aplikasi yang telah divalidasi. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Mendapatkan semua nilai untuk Identifier Aplikasi dalam urutan sumber. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Mendapatkan jenis barcode yang digunakan untuk menyandikan GS1 Digital Link ini. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Menyusun URI GS1 Digital Link yang tidak terkompresi. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Mendapatkan nilai pertama untuk Identifier Aplikasi. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Menginisialisasi instance ini dari URI GS1 Digital Link yang tidak terkompresi. Keadaan yang ada diganti hanya setelah URI yang diberikan berhasil diparsing. Jenis barcode yang dipilih dipertahankan. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Membuat teks kode GS1 independen yang berisi elemen GS1 saat ini. Informasi hanya URI tidak disertakan. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Mengembalikan URI GS1 Digital Link yang tidak terkompresi. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Memformat keadaan objek saat ini sebagai URI GS1 Digital Link yang tidak terkompresi. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Mencoba memparsing URI GS1 Digital Link yang tidak terkompresi dan mengembalikan kesalahan validasi terstruktur. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Memvalidasi URI GS1 Digital Link yang tidak terkompresi tanpa membuat objek. |

### Lihat Juga

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


