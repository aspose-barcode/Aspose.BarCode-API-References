---
title: "Kelas Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters. Menyimpan informasi metadata MacroPdf417 dari barcode yang dikenali dalam C++."
type: docs
weight: 2800
url: /id/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Menyimpan informasi metadata MacroPdf417 dari kode batang yang dikenali

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Bendera yang menunjukkan bahwa barcode MicroPdf417 dienkode dengan kata kode emulasi Code 128 908, 909, 910, atau 911. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** apakah semua parameter hanya memiliki nilai default |
| [get_IsLinked](./get_islinked/)() const | Bendera yang menunjukkan bahwa barcode harus terhubung ke barcode 1D. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Nama penerima Macro PDF417 (opsional). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Checksum Macro PDF417 (opsional). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Mendapatkan ID file barcode, hanya tersedia dengan MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Nama file Macro PDF417 (opsional). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Ukuran file Macro PDF417 (opsional). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Mendapatkan ID segmen barcode, hanya tersedia dengan MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Mendapatkan jumlah segmen barcode macro pdf417. Nilai default adalah -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Nama pengirim Macro PDF417 (opsional). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Menunjukkan apakah segmen tersebut adalah segmen terakhir dari file Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Stempel waktu Macro PDF417 (opsional). |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [Pdf417ExtendedParameters](./). |
## Catatan


Contoh ini menunjukkan cara mendapatkan metadata Macro Pdf417.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## Lihat Juga

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
