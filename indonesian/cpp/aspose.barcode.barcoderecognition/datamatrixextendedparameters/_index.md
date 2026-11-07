---
title: "Kelas Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters. Menyimpan data khusus dari kode batang DataMatrix yang dikenali dalam C++."
type: docs
weight: 1500
url: /id/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Menyimpan data khusus dari kode batang [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) yang dikenali

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** apakah semua parameter hanya memiliki nilai default |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Mendapatkan ID dari kode batang mode structured append [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/). ID dimulai dari 1 dan harus kurang atau sama dengan jumlah kode batang. Nilai default adalah -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Mendapatkan jumlah kode batang mode structured append [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/). Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Mendapatkan ID dari kode batang mode structured append [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/). ID dimulai dari 1 dan harus kurang atau sama dengan jumlah kode batang. Nilai default adalah -1. |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [DataMatrixExtendedParameters](./). |
## Catatan


Contoh ini menunjukkan cara mendapatkan nilai mentah [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## Lihat Juga

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
