---
title: "Kelas GS1Codetext"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "kelas Aspose.BarCode.ComplexBarcode.GS1Codetext. Mewakili kode teks GS1 untuk enkoding dan dekoding sebagai urutan terurut elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan. Representasi dalam tanda kurung memiliki bentuk AIvalueAIvalue. Tanda kurung buka literal di dalam nilai harus ditulis sebagai  ini adalah satu-satunya urutan pelarian yang didukung. Tanda kurung tutup di dalam nilai tidak memerlukan pelarian."
type: docs
weight: 530
url: /id/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Mewakili kode teks GS1 untuk enkoding dan dekoding sebagai urutan terurut elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan. Representasi dalam tanda kurung memiliki bentuk (AI)nilai(AI)nilai. Tanda kurung buka literal '(' di dalam nilai harus ditulis sebagai \(; ini satu-satunya urutan pelarian yang didukung. Tanda kurung tutup ')' di dalam nilai tidak memerlukan pelarian.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Mengambil atau mengatur tipe barcode yang digunakan untuk mengenkode kode teks GS1 ini. Tipe yang didukung adalah GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR, dan tipe GS1 DataBar. Nilai default adalah GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Mendapatkan jumlah elemen Identifier Aplikasi. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Mendapatkan salinan semua elemen dalam urutan sumber. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Mendapatkan sebuah elemen berdasarkan posisinya dalam urutan berurutan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Mengurai string elemen GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai. Tanda kurung buka literal '(' di dalam nilai harus ditulis sebagai \(; tidak ada urutan pelarian lain yang didukung, dan ')' tidak memerlukan pelarian. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Menambahkan elemen Identifier Aplikasi yang telah divalidasi. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Mendapatkan semua nilai untuk Identifier Aplikasi dalam urutan sumber. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Mengambil tipe barcode yang digunakan untuk mengenkode kode teks GS1 ini. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Membangun kode teks GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai. Tanda kurung buka literal dalam nilai di-escape sebagai \(. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Mendapatkan nilai pertama untuk Identifier Aplikasi. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Menginisialisasi instance ini dari kode teks GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai. Elemen yang ada hanya diganti setelah kode teks yang diberikan berhasil diurai. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Mengembalikan representasi GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Mencoba mengurai string elemen GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai dan mengembalikan kesalahan validasi terstruktur. Tanda kurung buka literal '(' di dalam nilai harus ditulis sebagai \(; tidak ada urutan pelarian lain yang didukung, dan ')' tidak memerlukan pelarian. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Memvalidasi string elemen GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai tanpa membuat objek. Tanda kurung buka literal '(' di dalam nilai harus ditulis sebagai \(; tidak ada urutan pelarian lain yang didukung, dan ')' tidak memerlukan pelarian. |

### Lihat Juga

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


