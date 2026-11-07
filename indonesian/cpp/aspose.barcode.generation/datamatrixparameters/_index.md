---
title: "kelas Aspose::BarCode::Generation::DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "kelas Aspose::BarCode::Generation::DataMatrixParameters. Parameter DataMatrix dalam C++."
type: docs
weight: 2000
url: /id/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


Parameter DataMatrix.

```cpp
class DataMatrixParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [get_EccType](./get_ecctype/)() const | Mendapatkan tipe ECC DataMatrix. Nilai default: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Mendapatkan pengkodean ECI. Digunakan ketika EncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Mode pengkodean kode batang Datamatrix. Nilai default: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. Nilai default: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh pengkodean yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan [DataMatrixEccType.Ecc200](../datamatrixecctype/) atau [DataMatrixEccType.EccAuto](../datamatrixecctype/). Tidak dapat digunakan dengan [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Nilai default: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | ID barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Jumlah barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | ID file untuk mode Structured Append pada kode batang Datamatrix. Nilai default: 0 |
| [get_Version](./get_version/)() const | Mendapatkan ukuran simbol Datamatrix. Nilai default: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Mengatur tipe ECC Datamatrix. Nilai default: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Mengatur enkoding ECI. Digunakan ketika EncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Mode pengkodean kode batang Datamatrix. Nilai default: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. Nilai default: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh pengkodean yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan [DataMatrixEccType.Ecc200](../datamatrixecctype/) atau [DataMatrixEccType.EccAuto](../datamatrixecctype/). Tidak dapat digunakan dengan [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Nilai default: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | ID barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Jumlah barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | ID file untuk mode Structured Append pada kode batang Datamatrix. Nilai default: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Mengatur ukuran simbol Datamatrix. Nilai default: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [DataMatrixParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
