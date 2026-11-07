---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters kelas"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters kelas. Menyimpan data khusus dari kode batang DotCode yang dikenali dalam C++."
type: docs
weight: 2000
url: /id/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


Menyimpan data khusus dari kode batang DotCode yang dikenali

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** apakah semua parameter hanya memiliki nilai default |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Mendapatkan ID dari kode batang mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah kode batang. Nilai default adalah -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Mendapatkan jumlah kode batang mode penambahan terstruktur DotCode. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35. |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [DotCodeExtendedParameters](./). |
## Catatan


Contoh ini menunjukkan cara mendapatkan nilai mentah DotCode
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## Lihat Juga

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
