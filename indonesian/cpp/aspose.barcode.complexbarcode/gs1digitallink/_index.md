---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink kelas"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink kelas. Mewakili kode teks GS1 Digital Link untuk penyandian dan penguraian sebagai urutan terurut elemen Application Identifier. Urutan sumber dan Application Identifier yang berulang dipertahankan. Kode teks yang dibangun adalah URI GS1 Digital Link yang tidak terkompresi. Parameter kueri Non-GS1 dan fragmen URI diabaikan saat parsing di C++."
type: docs
weight: 600
url: /id/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Menrepresentasikan teks kode GS1 Digital Link untuk penyandian dan penguraian sebagai urutan berurutan elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan. Teks kode yang dibangun adalah URI GS1 Digital Link yang tidak terkompresi. Parameter kueri non-GS1 dan fragmen URI diabaikan saat parsing.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Menambahkan elemen Application Identifier yang telah divalidasi. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Membuat GS1 Digital Link dengan menyalin semua elemen dari kode teks GS1 dan memilih satu-satunya kunci utama yang tersedia. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Membuat GS1 Digital Link dengan menyalin semua elemen dari kode teks GS1 dan menggunakan kunci utama yang ditentukan. |
| [get_BarcodeType](./get_barcodetype/)() const | Mendapatkan tipe barcode yang digunakan untuk menyandikan GS1 Digital Link ini. Tipe yang didukung adalah QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF, dan Code128. Nilai default adalah QR. |
| [get_Count](./get_count/)() | Mendapatkan jumlah elemen Application Identifier. |
| [get_Elements](./get_elements/)() | Mendapatkan salinan semua elemen dalam urutan sumber. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Mendapatkan Application Identifier yang digunakan sebagai kunci utama Digital Link. Null berarti kunci utama dipilih secara otomatis ketika URI dibangun. |
| [get_UriStem](./get_uristem/)() const | Mendapatkan awalan URI absolut sebelum segmen jalur kunci utama GS1. Bagian dasar tidak mengandung string kueri atau fragmen. |
| [GetAll](./getall/)(System::String) | Mendapatkan semua nilai untuk Identifier Aplikasi dalam urutan sumber. |
| [GetBarcodeType](./getbarcodetype/)() override | Mendapatkan jenis barcode yang digunakan untuk mengkodekan GS1 Digital Link ini. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Membuat URI GS1 Digital Link yang tidak terkompresi. |
| [GetFirst](./getfirst/)(System::String) | Mendapatkan nilai pertama untuk Identifier Aplikasi. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Menginisialisasi GS1 Digital Link kosong dengan URI stem yang ditentukan. Kunci utama dipilih secara otomatis ketika tepat satu kandidat kunci utama ada. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Menginisialisasi GS1 Digital Link kosong dengan URI stem dan kunci utama yang ditentukan. |
| [idx_get](./idx_get/)(int32_t) | Mendapatkan elemen berdasarkan posisinya dalam urutan terurut. |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance ini dari URI GS1 Digital Link yang tidak terkompresi. Status yang ada diganti hanya setelah URI yang diberikan berhasil diurai. Jenis barcode yang dipilih dipertahankan. |
| static [Parse](./parse/)(System::String) | Menganalisis URI GS1 Digital Link yang tidak terkompresi. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Mengatur jenis barcode yang digunakan untuk mengkodekan GS1 Digital Link ini. Jenis yang didukung adalah QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF, dan Code128. Nilai default adalah QR. |
| [ToGS1Codetext](./togs1codetext/)() | Membuat codetext GS1 independen yang berisi elemen GS1 saat ini. Informasi hanya URI tidak disertakan. |
| [ToString](./tostring/)() const override | Mengembalikan URI GS1 Digital Link yang tidak terkompresi. |
| [ToUriString](./touristring/)() | Memformat status objek saat ini sebagai URI GS1 Digital Link yang tidak terkompresi. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Mencoba mengurai URI GS1 Digital Link yang tidak terkompresi dan mengembalikan kesalahan validasi terstruktur. |
| static [Validate](./validate/)(System::String) | Memvalidasi URI GS1 Digital Link yang tidak terkompresi tanpa membuat objek. |
## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
