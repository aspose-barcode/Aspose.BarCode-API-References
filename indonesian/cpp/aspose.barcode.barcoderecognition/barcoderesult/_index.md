---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult kelas"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult kelas. Menyimpan data kode batang yang dikenali seperti tipe SingleDecodeType, **System::String** codetext, parameter BarCodeRegionParameters region, dan parameter lainnya dalam C++."
type: docs
weight: 700
url: /id/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Menyimpan data kode batang yang dikenali seperti tipe [SingleDecodeType](../singledecodetype/), **System::String** codetext, region [BarCodeRegionParameters](../barcoderegionparameters/) dan parameter lainnya

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Membuat salinan kelas [BarCodeResult](./). |
| [Clone](./clone/)() override | Membuat salinan kelas [BarCodeResult](./). |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BarCodeResult](./) yang ditentukan. |
| [get_CodeBytes](./get_codebytes/)() const | Mendapatkan byte kode yang terenkode |
| [get_CodeText](./get_codetext/)() const | Mendapatkan teks kode |
| [get_CodeType](./get_codetype/)() const | Mendapatkan tipe kode batang |
| [get_CodeTypeName](./get_codetypename/)() | Mendapatkan nama tipe kode batang |
| [get_Confidence](./get_confidence/)() const | Mendapatkan tingkat kepercayaan pengenalan kode batang yang dikenali |
| [get_Extended](./get_extended/)() const | Mendapatkan parameter tambahan dari kode batang yang dikenali |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Mendapatkan hasil evaluasi kualitas simbol ISO/IEC untuk kode batang yang dikenali. |
| [get_ReadingQuality](./get_readingquality/)() const | Mendapatkan kualitas pembacaan. Berfungsi untuk kode batang 1D dan pos. |
| [get_Region](./get_region/)() const | Mendapatkan wilayah kode batang |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Mendapatkan teks kode dengan enkoding. |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [BarCodeResult](./) ini. |
## Catatan


Contoh ini menunjukkan cara memperoleh [BarCodeResult](./).
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
