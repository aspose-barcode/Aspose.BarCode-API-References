---
title: "Kelas Aspose::BarCode::Generation::AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::Generation::AztecParameters. Parameter Aztec dalam C++."
type: docs
weight: 300
url: /id/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Parameter Aztec.

```cpp
class AztecParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [get_ECIEncoding](./get_eciencoding/)() const | Mendapatkan enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Mendapatkan mode enkode Aztec. Nilai default: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Tingkat koreksi kesalahan dari tipe barcode Aztec. Nilai harus antara 5 hingga 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [get_LayersCount](./get_layerscount/)() const | Mendapatkan jumlah lapisan simbol Aztec. Jumlah lapisan harus berada dalam rentang 1 hingga 3 untuk mode Kompak dan dalam rentang 1 hingga 32 untuk mode Jangkauan Penuh. Nilai default: 0 (otomatis). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus berada dalam rentang 1 hingga jumlah barcode. Nilai default: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | ID file untuk mode Structured Append pada barcode Aztec (field opsional). ID file tidak boleh mengandung spasi. Nilai default: string kosong |
| [get_SymbolMode](./get_symbolmode/)() const | Mendapatkan mode Simbol Aztec. Nilai default: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Mengatur enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Mengatur mode enkode Aztec. Nilai default: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Tingkat koreksi kesalahan dari tipe barcode Aztec. Nilai harus antara 5 hingga 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Mengatur jumlah lapisan simbol Aztec. Jumlah lapisan harus berada dalam rentang 1 hingga 3 untuk mode Kompak dan dalam rentang 1 hingga 32 untuk mode Jangkauan Penuh. Nilai default: 0 (otomatis). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus berada dalam rentang 1 hingga jumlah barcode. Nilai default: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | ID file untuk mode Structured Append pada barcode Aztec (field opsional). ID file tidak boleh mengandung spasi. Nilai default: string kosong |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Mengatur mode Simbol Aztec. Nilai default: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [AztecParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
