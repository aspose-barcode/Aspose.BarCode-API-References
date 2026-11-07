---
title: "kelas Aspose::BarCode::ComplexBarcode::GS1Codetext"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext kelas. Mewakili codetext GS1 untuk enkoding dan dekoding sebagai urutan terurut elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan. Representasi dalam kurung memiliki bentuk (AI)value(AI)value. Tanda kurung buka literal ''('' di dalam nilai harus ditulis sebagai (; ini satu-satunya urutan pelolosan yang didukung. Tanda kurung tutup '')'' di dalam nilai tidak memerlukan pelolosan dalam C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Menrepresentasikan teks kode GS1 untuk penyandian dan penguraian sebagai urutan berurutan elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan. Representasi dalam kurung memiliki format (AI)nilai(AI)nilai. Tanda kurung buka literal '(' di dalam nilai harus ditulis sebagai (; ini satu-satunya urutan pelolosan yang didukung. Tanda kurung tutup ')' di dalam nilai tidak memerlukan pelolosan.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Menambahkan elemen Application Identifier yang telah divalidasi. |
| [get_BarcodeType](./get_barcodetype/)() const | Mendapatkan jenis barcode yang digunakan untuk mengkodekan codetext GS1 ini. Jenis yang didukung adalah GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR, dan tipe GS1 DataBar. Nilai default adalah GS1Code128. |
| [get_Count](./get_count/)() | Mendapatkan jumlah elemen Application Identifier. |
| [get_Elements](./get_elements/)() | Mendapatkan salinan semua elemen dalam urutan sumber. |
| [GetAll](./getall/)(System::String) | Mendapatkan semua nilai untuk Identifier Aplikasi dalam urutan sumber. |
| [GetBarcodeType](./getbarcodetype/)() override | Mendapatkan jenis barcode yang digunakan untuk mengkodekan codetext GS1 ini. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Membuat codetext GS1 dalam kurung dengan format (AI)value(AI)value. Tanda kurung buka literal dalam nilai diloloskan sebagai (. |
| [GetFirst](./getfirst/)(System::String) | Mendapatkan nilai pertama untuk Identifier Aplikasi. |
| [GS1Codetext](./gs1codetext/)() | Menginisialisasi codetext GS1 kosong. |
| [idx_get](./idx_get/)(int32_t) | Mendapatkan elemen berdasarkan posisinya dalam urutan terurut. |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance ini dari codetext GS1 dalam kurung dengan format (AI)value(AI)value. Elemen yang ada diganti hanya setelah codetext yang diberikan berhasil diurai. |
| static [Parse](./parse/)(System::String) | Menganalisis string elemen GS1 dalam kurung dengan format (AI)value(AI)value. Tanda '(' literal di dalam nilai harus ditulis sebagai (; tidak ada urutan pelolosan lain yang didukung, dan ')' tidak memerlukan pelolosan. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Mengatur jenis barcode yang digunakan untuk mengkodekan codetext GS1 ini. Jenis yang didukung adalah GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR, dan tipe GS1 DataBar. Nilai default adalah GS1Code128. |
| [ToString](./tostring/)() const override | Mengembalikan representasi GS1 dalam kurung dalam bentuk (AI)nilai(AI)nilai. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Mencoba mengurai string elemen GS1 dalam kurung dalam bentuk (AI)nilai(AI)nilai dan mengembalikan kesalahan validasi terstruktur. Tanda '(' literal di dalam nilai harus ditulis sebagai (; tidak ada urutan pelolosan lain yang didukung, dan ')' tidak memerlukan pelolosan. |
| static [Validate](./validate/)(System::String) | Memvalidasi string elemen GS1 dalam kurung dalam bentuk (AI)nilai(AI)nilai tanpa membuat objek. Tanda '(' literal di dalam nilai harus ditulis sebagai (; tidak ada urutan pelolosan lain yang didukung, dan ')' tidak memerlukan pelolosan. |
## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
