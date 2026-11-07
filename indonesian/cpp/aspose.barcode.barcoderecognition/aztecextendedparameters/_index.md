---
title: "kelas Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "kelas Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters. Menyimpan data khusus barcode Aztec yang dikenali dalam C++."
type: docs
weight: 300
url: /id/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Menyimpan data khusus dari kode batang Aztec yang dikenali

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** apakah semua parameter hanya memiliki nilai default |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Mendapatkan ID barcode mode penambahan terstruktur Aztec. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Mendapatkan jumlah barcode mode penambahan terstruktur Aztec. Nilai default adalah 0. Jumlah harus berupa nilai antara 1 hingga 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Mendapatkan File ID mode penambahan terstruktur Aztec. Nilai default adalah string kosong |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [AztecExtendedParameters](./). |
## Catatan


Contoh ini menunjukkan cara mendapatkan nilai mentah Aztec
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## Lihat Juga

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
